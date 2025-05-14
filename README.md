# 📊 Employee Survey Data Analysis – Excel Project

This project is based on the Excel-based assessment provided by **PlacementDost** for interns. The goal is to demonstrate practical data analysis skills using real employee survey data in Microsoft Excel.

---

## 🛠 Tools Used

- Microsoft Excel
- Excel Add-ins: Solver, Analysis ToolPak
- Power Pivot (for DAX calculations)
- Pivot Tables and Pivot Charts

---

## ✅ Summary of Tasks

![image](https://github.com/user-attachments/assets/a48a8547-70d3-4a03-8f08-ccf8352c2297)


1. **Data Import and Cleanup**  
   - Imported survey data into Excel and cleaned missing/inconsistent entries.
     
    ![image](https://github.com/user-attachments/assets/45187be1-50e6-4784-a3b8-5f70bba48f39)


2. **Data Validation**  
   - Applied validation to ensure "Response" values are between 0 and 4.

     ![image](https://github.com/user-attachments/assets/95276ffe-0fd6-4037-bb9a-8015e1fc3e66)


3. **Conditional Formatting**  
   - Highlighted "Strongly Disagree" responses using distinct formatting.

     ![image](https://github.com/user-attachments/assets/122d8436-bf31-4c18-91a1-ad6a98d9077c)


4. **IF and Nested IF Functions**  
   - Categorized responses as “Positive”, “Neutral”, or “Negative” based on their values.

     ![image](https://github.com/user-attachments/assets/e7f58e80-2640-44e6-9a95-0619ddf04ef5)


5. **VLOOKUP and HLOOKUP**  
   - Created a summary sheet displaying responses by department and question using lookup functions.

     VLOOKUP([@Question],'HR Survey Reponses'!H:I,2,FALSE)

6. **Pivot Table (Basic)**  
   - Analyzed average response values by department with slicers for filtering.

     ![image](https://github.com/user-attachments/assets/daf2b7f9-f2d2-481d-aa74-e6d5939d514a)


7. **Pivot Table – Calculated Fields**  
   - Added a calculated field to compute the overall average response for each question.

8. **Pivot Chart**  
   - Visualized the data using Pivot Charts based on the Pivot Table analysis.

     ![image](https://github.com/user-attachments/assets/b053f674-5ef0-42ec-a441-be149b21bb2a)


9. **INDEX-MATCH**  
   - Retrieved the corresponding response text for a given value using INDEX-MATCH.

     INDEX('HR Survey Reponses'!I:J,MATCH('HR Survey Reponses'!I2,'HR Survey Reponses'!I:I,0),2)

10. **Analysis with Excel Tables**  
    - Converted data to Table format and utilized table features for efficient analysis.

11. **Scenario Manager**  
    - Created and analyzed optimistic, realistic, and pessimistic response scenarios.

      ![image](https://github.com/user-attachments/assets/f7456208-5e59-46ae-be30-979c06894415)


12. **Solver Add-In**  
    - Used Solver to optimize response values to meet a target average under constraints.

      ![image](https://github.com/user-attachments/assets/ae43e5e5-dcb9-4fe1-8191-04db418eb555)


13. **Waterfall Chart**  
    - Visualized the cumulative impact of positive and negative responses for a specific department.

      ![image](https://github.com/user-attachments/assets/dcadb329-64b1-48b4-a862-c2fb7bb4dd14)


14. **Dynamic Named Ranges**  
    - Implemented dynamic ranges that auto-expand when new responses are added.

      ![image](https://github.com/user-attachments/assets/b38e9231-275d-4d3d-ac96-04309d42c4a4)


15. **Data Model Relationships**  
    - Built relationships between tables to support advanced analysis.

      ![image](https://github.com/user-attachments/assets/dc6d6a99-bdfc-4e91-8f17-ba6e84005cfb)


16. **DAX Measures**  
    - Used DAX formulas in Power Pivot to calculate average responses across all questions.

17. **Goal Seek**  
    - Applied Goal Seek to determine required changes to reach a specific overall average.

      ![image](https://github.com/user-attachments/assets/2a7b5160-8a76-492f-b55b-ebbebd756340)


18. **Advanced Dashboard**  
    - Developed an interactive Excel dashboard using dropdowns, buttons, and dynamic visuals.

      ![image](https://github.com/user-attachments/assets/bfb082f1-eedf-41ca-97c7-ffd388f62b74)

      ![image](https://github.com/user-attachments/assets/0be9f155-3ca5-46d5-9d62-177540dcad5d)



