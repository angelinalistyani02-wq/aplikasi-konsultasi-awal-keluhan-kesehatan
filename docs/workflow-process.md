# Workflow Process

## Document Purpose

This document describes the main operational processes within the system, helping readers understand how users and administrators interact with the system to achieve specific objectives.

## Process Summary

The operational processes within the system are interconnected to support the delivery of preliminary health information to users. Data maintenance performed by administrators ensures that disease and symptom information remains available and up to date. Meanwhile, user processes utilize this data to access disease information and conduct preliminary consultations based on selected symptoms.

### Disease Information Access Process

**Purpose**
Provides access to disease information available in the system, allowing users to gain an initial understanding of specific health conditions.

**Actors**
User.

**Preconditions**
The user has accessed the application.

**Workflow Steps:**
1. The user accesses the Disease List menu.
2. The system displays the available diseases.
3. The user selects a disease.
4. The system displays detailed information about the selected disease.

**Expected Outcome**
The system displays detailed information about the selected disease to the user.

### User Consultation Process

**Purpose**
Helps users obtain preliminary information about potential health conditions based on their selected symptoms.

**Actors**
User.

**Preconditions**
Symptom data, disease data, and the associated symptom relationships are available in the system.

**Workflow Steps:**
1. The user accesses the consultation menu.
2. The system displays the available symptoms.
3. The user selects symptoms that match their experienced condition.
4. The user submits the selected symptoms to proceed with the consultation.
5. The system processes the selected symptoms.
6. The system displays the consultation results.

**Alternative Flow (Retake Consultation):**
1. The user chooses to restart the consultation.
2. The system clears the previously selected symptoms.
3. The user returns to the symptom selection stage.
4. The consultation process starts again from the symptom selection stage.

**Expected Outcome**
The user receives consultation results based on the selected symptoms.

### Disease Data Maintenance Process

**Purpose**
Ensures that the disease information used by the system remains available and up to date to support the delivery of information to users.

**Actors**
Administrator.

**Preconditions**
The administrator has successfully logged in to the system.

**Workflow Steps:**
1. The administrator accesses the Disease Data menu.
2. The system displays the available disease data.
3. The administrator maintains the disease data as needed.
4. The system saves the changes to the disease data.
5. The system displays the updated disease data.

**Expected Outcome**
Disease data remains properly maintained and available to support the delivery of information to users.

### Symptom Data Maintenance Process

**Purpose**
Ensures that the symptom information used in the consultation process remains available and up to date.

**Actors**
Administrator.

**Preconditions**
The administrator has successfully logged in to the system.

**Workflow Steps:**
1. The administrator accesses the Symptom Data menu.
2. The system displays the available symptom data.
3. The administrator maintains the symptom data as needed.
4. The system saves the changes to the symptom data.
5. The system displays the updated symptom data.

**Expected Outcome**
Symptom data remains properly maintained and available for use in the consultation process.
