# Initial Health Symptom Consultation Application

## Project Overview

The Initial Health Symptom Consultation Application is an Android-based information system that helps users conduct preliminary health consultations based on selected symptoms.

The system is designed to provide preliminary information about potential health conditions before users seek further consultation with medical professionals.

The application uses the Dempster-Shafer method to analyze symptom data and generate potential diagnoses based on predefined rules and a knowledge base.

## Business Problem

Users often have difficulty understanding potential health conditions based on the symptoms they experience, particularly when determining the appropriate next steps for an initial consultation.

In addition, access to healthcare consultation services is not always readily available to all users.

To address these challenges, an information system was developed to help users obtain preliminary information about potential health conditions based on their selected symptoms.

## Proposed Solution

The system is designed to help users conduct preliminary health consultations by selecting symptoms through an Android-based application.

Users can select the symptoms they experience, and the system processes the selected data using the Dempster-Shafer method to generate preliminary information about potential health conditions.

The consultation results are presented as a brief explanation to help users understand possible next steps for seeking further medical consultation.

## Main Features

### User Features

- **Symptom Consultation**  
  Users can select their symptoms through the application to conduct a preliminary health consultation.

- **Diagnosis Results**  
  Users receive preliminary health information based on the selected symptoms and the consultation results.

- **Disease Information**  
  Users can view general information about diseases listed in the application.

### Admin Features

- **Disease Data Management**  
  Administrators can manage disease data.

- **Symptom Data Management**  
  Administrators can manage the symptom data used in the consultation process.

## System Workflow

1. Users select the symptoms they experience to initiate a preliminary consultation.
2. The system processes the selected symptom data.
3. The system performs calculations using the Dempster-Shafer method.
4. The system displays information about potential health conditions.

## Technology Used

**Development**
- Android Studio
- Java
- Firebase Realtime Database

**Method**
- Dempster-Shafer

## Data Structure

- **Disease Data**  
  Stores the list of diseases used in the consultation process.

- **Symptom Data**  
  Stores the symptoms that users can select during a consultation.

- **Diagnosis Relationship Data**  
  Stores the relationships between symptoms and diseases as the basis for analysis using the Dempster-Shafer method.

## Documentation

- [System Overview](docs/system-overview.md)
- [Feature Documentation](docs/feature-documentation.md)
- [Workflow Process](docs/workflow-process.md)
- [Data Structure](docs/data-structure.md)
- [Processing Logic](docs/processing-logic.md)
