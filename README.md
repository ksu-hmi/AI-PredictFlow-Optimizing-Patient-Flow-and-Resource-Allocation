# AI-PredictFlow-Optimizing-Patient-Flow-and-Resource-Allocation
This project focuses on using artificial intelligence (AI) and machine learning (ML) to improve patient flow and resource allocation in hospitals. The goal is to predict patient movements such as admissions, transfers, and discharges and optimize resource use, especially in busy areas like MedSurg and PCU. By making staffing and bed placement decisions more efficient, this tool aims to reduce delays, improve patient care, and ease the workload on hospital staff.

How It Works
Flagging During Admission Process:

The system starts its work when the provider in the Emergency Department (ED) places an order for a hospitalist consult. At this point, it flags the patient and begins suggesting possible locations based on available beds and hospital resources.
Once the hospitalist makes the final admission decision and places the order, the system refines its recommendations. Typically, the admission order includes the preferred location, such as MedSurg, PCU, or other specialty units.
Location Recommendations:

For hospitals with multiple similar floors or specialties, the system provides precise recommendations on where to place the patient. These recommendations consider factors such as bed availability, staff workload, and unit-specific capabilities.
By automating these suggestions, the system reduces the time house supervisors or throughput nurses spend manually checking floor-by-floor availability.
Integration with EHR Tools:

The system incorporates existing tools within EHR systems, such as Epic’s workload and acuity features. These features provide:
A workload number per patient to reflect the staff’s current demands.
An acuity number to measure the intensity of care required for each patient.

Example Scenario:
Floor 1 and Floor 2 both have 23 patients, but Floor 1 has a higher average workload and acuity. The system would recommend placing the new patient on Floor 2, ensuring fair distribution of resources and preventing staff burnout.
Customizable Filters:

The system is designed to account for unit-specific requirements, such as medication capabilities or specialty care. Filters ensure that only appropriate units are recommended, while still leaving the final decision to house supervisors or throughput nurses.
Final Decision and Communication:

The system is a decision-support tool, not a replacement for human judgment. Supervisors and MDs retain the final authority over patient placement.
Communication remains essential, especially when patient orders are incomplete or specific conditions arise that require manual intervention.

Key Benefits

Efficiency: Speeds up the bed placement process by automating recommendations and reducing manual checks.

Fair Distribution: Avoids favoritism in bed assignments by using objective data like workload and acuity numbers.

Eases Supervisor Workload: Reduces the burden on house supervisors and throughput nurses by streamlining decisions.

Improves Patient Care: Ensures that patients are placed in the most suitable locations for their care needs.

Supports Communication: Facilitates collaboration between MDs, supervisors, and floor staff while providing actionable insights.

Dashboard Mockup

The dashboard mockup below illustrates how the system displays patient flow, workload, acuity, and recommendations for resource allocation.

![Dashboard Sample](https://github.com/user-attachments/assets/af6e59a3-7909-46b9-94ea-bddc5eaad7b2)

