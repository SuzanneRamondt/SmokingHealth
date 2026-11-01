# SmokingHealth

This repository contains the results of a FAIR data project by Group 25 for the University of Twente FAIR Data course (2025–2026). The project focuses on making a health and smoking dataset more **Findable, Accessible, Interoperable and Reusable (FAIR)**.

## Project overview

The original dataset contains information about individuals, including age, gender, BMI, cholesterol, blood pressure and smoking habits. It was converted from CSV into RDF/Turtle to improve data sharing and reuse.

Two derived properties were added, resulting in **15 properties in total**.

Each individual is represented as a person resource, connected to separate health-status and smoking-assessment resources. Measurements are represented as individual resources with corresponding values and units where applicable.
