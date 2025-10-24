## This project automates the RPA Challenge website using UiPath.  
**It extracts data from an Excel file and fills out the form automatically to complete all rounds as fast and accurately as possible.**  

- **Features:**

1) Download Excel File from website  
2) Reads input data from an Excel file.  
3) Automatically fills all form fields on the RPA Challenge website.  
4) Uses dynamic selectors to handle changing form field positions.  
5) Implements error handling (Business & System Exceptions).  
6) Logs execution details for debugging and monitoring.  
7) Supports multiple retries and delay controls for better performance.  
8) Handle error and and exceptions using Try Catch  


- **Key Concepts Demonstrated:**

1) Use of Try Catch for exception handling.  
2) Business and System Exception differentiation.  
3) Argument passing between workflows.  
4) Use of Simulate Type and delay tuning for speed optimization.  
5) DataTable filtering and iteration with For Each Row in DataTable.  
6) Conditional logic using If and Do While activities.  
7) Kill Process for Apss used.  

- **Performance Optimization:**

1) Used SimulateType and SimulateClick to increase speed.  
2) Minimized unnecessary delays (DelayBefore / DelayAfter).  


- **Output:**
Successfully filled form for all records with a success rate is 100% in 55625 millisecondes.  
