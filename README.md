# Farm Management App

## Piggery

### Database

- **Fattening**

  - Serial Number
  - Birthday
  - Mother
  - Father
  - Sex
  - Live Weight
  - Vaccinations
    - Date
    - Name of Vaccine
    - Dosage
    - Recorder
  - Weight Inspections
    - Date
    - Weight (kg)
    - Recorder
  - Cage Transfers
    - Date
    - Cage Location
    - Recorder
  - Health Issues
    - Date
    - Status/Condition
    - Recorder
  - Diet Changes
    - Date
    - Feed Formula
    - Feed Amount (kg)
    - Recorder
  - Disposal/Death
    - Date
    - Cause of Death
    - Recorder

- **Sow**

  - Serial Number
  - Birthday
  - Mother
  - Father
  - Sex
  - Live Weight
  - Number of nipples
  - Vaccinations
    - Date
    - Name of Vaccine
    - Dosage
    - Recorder
  - Weight Inspections
    - Date
    - Weight (kg)
    - Recorder
  - Cage Transfers
    - Date
    - Cage Location
    - Recorder
  - Health Records
    - Date
    - Status/Condition
    - Recorder
  - Health Issues
    - Date
    - Feed Formula
    - Feed Amount (kg)
    - Recorder
  - Mating
    - Date
    - Boar
    - Method (AI or actual breeding)
    - Recorder
  - Births
    - Date
    - Total Number of births
    - Total Number of live births
    - Children (Serial Numbers)
    - Recorder
  - Disposal/Death
    - Date
    - Cause of Death
    - Recorder

- **Boar**
  - Serial Number
  - Birthday
  - Mother
  - Father
  - Sex
  - Live Weight
  - Vaccinations
    - Date
    - Name of Vaccine
    - Dosage
    - Recorder
  - Weight Inspections
    - Date
    - Weight (kg)
    - Recorder
  - Cage Transfers
    - Date
    - Cage Location
    - Recorder
  - Health Issues
    - Date
    - Status/Condition
    - Recorder
  - Diet Changes
    - Date
    - Feed Formula
    - Feed Amount (kg)
    - Recorder
  - Matings
    - Date
    - Sow
    - Method (AI or actual breeding)
    - Recorder
- Disposal/Death
  - Date
  - Cause of Death
  - Recorder

### Human Resource

- Database
  - Name
  - Birthdate
  - Employment Start Date
  - Civil Status
  - Work History
    - Department
    - Tasks
      - Daily Tasks
        - Task Name
        - Inspection Date
        - Inspector
      - Weekly Tasks
        - Task Name
        - Inspection Date
        - Inspector
      - Monthly Tasks
        - Task Name
        - Inspection Date
        - Inspector
  - Shift Schedule
  - Hourly Rate
  - Attendance Records

### Weighing without a Scale

This procedure is reported to be accurate to within 3%.

- Input
  - Heart Girth (meters)
  - Length (meters)
- Output
  - Weight (kg)
    - 69.3 x Length x Heart Girth ^ 2
