# Processing Logic

## Document Purpose

This document explains the data processing logic performed by the system to generate information.

## Processing Logic Overview

The system's processing logic is built on the logical relationships between data entities. Symptom Data is linked to Diagnosis Relationship Data, which serves as the knowledge base used to generate a diagnosis. Meanwhile, Disease Data provides detailed information about the disease selected by the user.

## Initial Consultation Processing Logic

### Input   
The system receives Symptom Data as input for the initial consultation process. This data serves as the basis for identifying potential diseases.

### Processing

Disease identification is performed by using the relationships between Symptom Data and Diagnosis Relationship Data within the system. Diagnosis Relationship Data serves as the knowledge base that connects symptoms with diseases to support the identification process.

Within the knowledge base, Symptom Data is used to analyze the relationship between selected symptoms and potential diseases. The results of this analysis are then used to generate a diagnosis.

### Output    
The diagnosis represents the disease identified through the processing results. The diagnosis is then displayed to the user.

## Disease Information Presentation Logic

### Input   
The user selects a disease in the system. This selection determines which Disease Data record the system uses as the source of disease information.

### Processing   
The system retrieves and organizes Disease Data for presentation. The selected disease data is then used to provide detailed information about the disease.

### Output     
Detailed disease information is produced as the output of the processing and is used to present information to the user.
