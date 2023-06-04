# Patient Portal API RAML

This RAML defines the API for a patient portal. The API allows patients to view their medical records, schedule appointments, and manage their medications.

## Getting Started

To get started with this API on Anypoint Platform, you will need to do the following:

1. Import the RAML file into Anypoint Platform.
2. Create a new API in Anypoint Platform using the imported RAML file.
3. Deploy the API to a runtime environment.

## Endpoints

The following endpoints are available:

- /patients: Get all patients.
- /patients/:id: Get a patient by ID.
- /doctors: Get all doctors.
- /doctors/:id: Get a doctor by ID.
- /medications: Get all medications.
- /medications/:id: Get a medication by ID.
- /appointments: Get all appointments.
- /appointments/:id: Get an appointment by ID.

## Data Models

The following data models are used:
- Patients
A patient is a person who is registered with the patient portal. A patient has a name, date of birth, and medical record number.

- Doctors
A doctor is a healthcare professional who is authorized to treat patients. A doctor has a name, specialty, and license number.

- Medications
A medication is a drug or other substance that is used to treat a medical condition. A medication has a name, dosage, and frequency of administration.

- Appointments
An appointment is a scheduled meeting between a patient and a doctor. An appointment has a date, time, and location.
- `Patient`: Represents a patient.
- `Doctor`: Represents a doctor.
- `Medication`: Represents a medication.
- `Appointment`: Represents an appointment.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork this repository.
2. Create a new branch for your changes.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Submit a pull request.

## License

This project have no license. It is made for educational purpose by [WeirdOCourses](https://weirdocourses.com/)- see the [LICENSE.md](LICENSE.md) file for details.
