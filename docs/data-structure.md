# Data Structure

## 1. Document Purpose

This document provides an overview of the data used in the system, the purpose of each data entity, and the relationships between them.

## 2. Data Structure Overview

The system uses three types of data: Disease Data, Symptom Data, and Diagnosis Relationship Data. Each serves a different purpose within the system.

Disease Data provides disease information displayed to users, Symptom Data serves as input for the consultation process, and Diagnosis Relationship Data connects symptoms and diseases to support the consultation process. Together, these three data entities support the consultation workflow and the presentation of information to users.

## 3. Disease Data Structure

**Purpose**

Disease Data serves as the source of disease information displayed to users.

**Stored Information**

- **Disease Name** identifies the disease displayed to users.
- **Disease Description** provides a general overview of the disease.
- **Initial Treatment Information** provides users with information about initial measures that may be taken for the disease.

**System Usage**

1. Displays the disease name from the consultation results in the Diagnosis Results feature.
2. Displays detailed disease information in the Disease Information feature.

**Data Relationships**

Disease Data is connected to Symptom Data through Diagnosis Relationship Data to support the consultation process.

## 4. Symptom Data Structure

**Purpose**

Symptom Data provides a list of symptoms available for users to select during a consultation.

**Stored Information**

- **Symptom Code** identifies each symptom stored in the system.
- **Symptom Name** provides the label displayed to users when selecting symptoms during a consultation.
- **Symptom Weight** is an attribute of Symptom Data used by the system as an input value for diagnosis calculations.

**System Usage**

1. Displays the list of symptoms in the Symptom Consultation feature.
2. Provides the list of symptoms that users can select during the consultation process.

**Data Relationships**

Symptom Data is connected to Disease Data through Diagnosis Relationship Data to support the consultation process.

## 5. Diagnosis Relationship Data Structure

**Purpose**

Diagnosis Relationship Data serves as the knowledge base that connects Symptom Data and Disease Data.

**Stored Information**

1. **Disease Relationship** identifies the disease associated with a particular symptom within the diagnostic knowledge base.
2. **Symptom Relationship** identifies the symptoms associated with a particular disease within the diagnostic knowledge base.
3. **Belief Value** represents the level of expert confidence in the relationship between a disease and a symptom.

**System Usage**

1. Provides the knowledge base used by the system during the consultation process.

**Data Relationships**

Diagnosis Relationship Data connects Disease Data and Symptom Data within the system.

## 6. Data Structure Diagram

This section presents a visual representation of the main data structures used in the system.

<p align="center">
  <img src="/assets/structure-data-diagram.png" width="600">
</p>

<p align="center">
  <em>Data Structure Overview</em>
</p>

The diagram above illustrates the main data structures used in the system. Diagnosis Relationship Data acts as the link between Disease Data and Symptom Data, forming the knowledge base used by the system.
