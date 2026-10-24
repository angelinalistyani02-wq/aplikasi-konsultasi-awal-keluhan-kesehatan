# System Overview

## Purpose

The system helps users conduct preliminary health consultations based on their selected symptoms. The selected symptoms are processed to provide preliminary information about potential health conditions before users decide whether to seek further consultation with healthcare professionals.

## User Roles

**User**

General users who access the application to conduct preliminary consultations based on their selected symptoms and obtain initial information about potential health conditions.

**Responsibilities:**
- Conduct consultations based on selected symptoms.
- View consultation results related to potential health conditions.
- Access general information about diseases available in the application.

**Admin**

A doctor or medical expert responsible for managing the data used in the preliminary health consultation process.

**Responsibilities:**
- Manage symptom data.
- Manage disease data and disease information.
- Maintain the data used in the consultation process.

## System Scope

### In Scope

- Accepting symptoms selected by users.
- Processing symptoms based on the expert knowledge base.
- Providing preliminary information about potential health conditions.
- Providing general disease information.
- Managing symptom and disease data, including the symptom relationships defined for each disease.

### Out of Scope

- Providing medical diagnoses as a substitute for healthcare professionals.
- Conducting real-time consultations with users.
- Providing medical treatment in the capacity of a doctor.
- Directly connecting users with healthcare professionals.

## High-Level System Flow

1. Users select symptoms available in the application.
2. The system receives the symptoms selected by the users.
3. The system processes the selected symptoms using the available knowledge base.
4. The system analyzes the symptoms to generate preliminary information about potential health conditions.
5. The system displays information about potential health conditions to the users.

## Main Data Used

### Symptom Data

Used as the input source for the preliminary consultation process. This data contains the list of symptoms available for users to select.

### Disease Data

Used to provide disease information that helps users understand potential health conditions and relevant initial treatment information.

### Diagnosis Relationship Data

Contains the relationships between symptom data and disease data used in the analysis process to generate preliminary information about potential health conditions.
