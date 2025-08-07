<h1>ETL Development: Java, External Integrations & Performance Optimization</h1>


<h2>Overview</h2>
Implemented Java code using Talend’s Java components, integrated external libraries and components to address specific use cases, and applied performance optimization techniques to improve job efficiency and scalability.
<br />


<h2>Key Highlights</h2>

- **Java Components:** Used Talend Java components such as `tJava`, `tJavaRow`, and `tJavaFlex` to execute basic operations, including nested for loops with conditional (if) statements.  

- **External Libraries:** Integrated external libraries via `tLibraryLoad` from Talend’s Maven repository. Added `commons-lang3-3.10.jar` for string manipulation and applied it in a transformation using `tMap` after importing the required package and class name in the Advanced Settings of the `tLibraryLoad`.

- **External Components:** Integrated external components (`tFileOutputPDF`) to export data from Talend into a PDF file. Enabled the component by downloading it and adding it in Window → Preferences → Talend → Components. 

- **Hash Components:** Used the `tHashOutput` and `tHashInput` components to enable selective reads, control record matching, and clear cached data during jobs to improve performance.

- **JVM Parameters:** Configured JVM arguments in Run → Advanced Settings by enabling “Use Specific JVM Arguments,” and adjusting memory (RAM) allocation to optimize job execution. 

- **Parallel Execution:** Enabled parallel execution in Job → Extra by checking “Multi-Thread Execution” to run multiple sub-jobs in parallel. Also activated parallel execution in iterations by enabling “Parallel Execution” in iteration links, such as within the `tLoop` component.

<h2>Skills </h2>

Talend Open Studio, Java Components, External Libraries & Components Integration, Performance Optimization.

<h2>Documentation:</h2>

<p align="center">
1.1 tJava - Job Designer Workflow & Code <br/>
<img src="https://github.com/user-attachments/assets/71698659-2f56-4a32-8b1d-4ea4511f56f6" height="80%" width="80%" alt="Schema Handling"/>
<br />
<br />
1.2 tJavaRow - Job Designer Workflow & Code  <br/>
<img src="https://github.com/user-attachments/assets/67f06533-54b9-474f-90f3-0bdb58901da4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
1.3 tJavaFlex - Job Designer Workflow <br/>
<img src="https://github.com/user-attachments/assets/45538be4-534d-44c4-92d2-16b94bc5690e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
1.4 tJavaFlex - Code  <br/>
<img src="https://github.com/user-attachments/assets/6218c44e-ff1a-43d9-85da-ad3a8078fe53" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2.1 External Libraries - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/fae9f7be-bf02-49a5-bbc6-163745d5710a" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2.2 External Libraries - tMap Mapping Configuration  <br/>
<img src="https://github.com/user-attachments/assets/1e9a8c06-69aa-4484-9dfe-e9134d1d4968" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3.1 External Components - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/651a5c55-0f46-4ef5-8a94-758c0365a175" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
3.2 External Components - Importing & Configuration  <br/>
<img src="https://github.com/user-attachments/assets/d8426523-a17b-40e8-8506-769ac5578a07" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
4.1 Hash Components - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/db92f734-2fd3-4f73-9fcd-140fe8b7a306" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
4.2 Hash Components - Data Output Results  <br/>
<img src="https://github.com/user-attachments/assets/e8a6160c-c1b6-46ba-9e9f-f57f4829fe36" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
5.1 JVM Parameters - Job Designer Workflow & Settings <br/>
<img src="https://github.com/user-attachments/assets/05c2a8c0-7ac2-454e-996d-72eda75eb41e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
6.1 Parallel Execution - Job Designer Workflow & Settings  <br/>
<img src="https://github.com/user-attachments/assets/8a18ce74-ba84-43ba-aba7-1a9a41262e85" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
