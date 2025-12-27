What This Project Does
This system automatically analyzes customer support tickets and converts raw, unstructured text into meaningful insights. It helps support teams understand what the issue is, how urgent it is, and when it must be resolved, all using a rule-based approach in Python.
Why This Project Is Useful
Support teams often receive large volumes of tickets written in different formats and styles. Manually reading and prioritizing them takes time. This project reduces that effort by:
Standardizing ticket descriptions
Grouping similar problems together
Assigning urgency levels
Calculating SLA deadlines automatically
Workflow
Load customer support ticket data from a CSV file
Clean and normalize ticket descriptions
Identify the issue type using keyword rules
Assign priority based on urgency words
Calculate SLA hours and due time
Generate a final structured report
Key Outcomes
Faster ticket categorization
Clear priority assignment (P0–P3)
SLA-aware due time calculation
Manager-friendly summary report
Ready-to-use final CSV output
Tools and Technologies
Python
Pandas
Google Colab
Input and Output
Input:
CSV file containing customer support tickets
Output:
Processed CSV file with issue category, priority level, SLA hours, and due time
