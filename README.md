# PA4
This Jupyter Notebook contains the solution for Programming Assignment 4 of ECE 2112. 

### Intended Learning Outcomes
1. Filter tabular data using several categorical and numerical conditions;
2. Construct focused DataFrames by selecting relevant features;
3. Summarize the relationship between categorical features and a numerical variable; and
4. Communicate a data comparison using clear and correctly labeled plots.

### PROBLEM A: VISAYAS COMMUNICATION DATAFRAME
Create a DataFrame named VisComm containing students whose Hometown is Visayas and whose Track
is Communication.

- First import the files


<img width="1388" height="152" alt="image" src="https://github.com/user-attachments/assets/b0c97fdd-1d30-4e2c-aa10-6125280163ef" />

- Code to show the retained order:

<img width="531" height="87" alt="image" src="https://github.com/user-attachments/assets/a87aa025-72fb-4222-aae6-e299a0406199" />

OUTPUT:
<img width="180" height="203" alt="image" src="https://github.com/user-attachments/assets/d486cf73-880b-4345-88c1-30da4920eba6" />

- Codes that show students whose Hometown is Visayas and whose Track
is Communication.

<img width="787" height="117" alt="image" src="https://github.com/user-attachments/assets/4362486c-cba8-46d2-b8b5-86edd3210b44" />

OUTPUT:

<img width="442" height="231" alt="image" src="https://github.com/user-attachments/assets/d8145443-2599-4b1c-87c0-d427d007d0c8" />
<img width="481" height="81" alt="image" src="https://github.com/user-attachments/assets/f5383bc4-2396-4a48-81c5-3716a8ea9052" />


### PROBLEM B: VISAYAS FEMALE DATAFRAME
Create a second DataFrame named VisFemale containing students whose Hometown is Visayas and
whose Gender is Female. Retain only: Name, Track, GEAS, Electronics, Average

-Code to show students whose Hometown is Visayas and whose Gender is Female:

<img width="712" height="139" alt="image" src="https://github.com/user-attachments/assets/8fcac62c-4751-4111-8cdd-1d82889cea73" />

OUTPUT:

<img width="555" height="275" alt="image" src="https://github.com/user-attachments/assets/ba7e0d39-4582-4e46-ac27-70108639ef39" />

-Code that shows the average is atleast 60:

<img width="570" height="128" alt="image" src="https://github.com/user-attachments/assets/e39d6f55-8187-499c-a148-c3e562848882" />


OUTPUT:
<img width="491" height="207" alt="image" src="https://github.com/user-attachments/assets/99da47af-1560-4f07-a0e8-f3973937b60b" />

### PROBLEM C: CATEGORY-AVERAGE VISUALIZATION
Examine how the recorded Average differs across the three categorical features Track, Gender, and Hometown.
a. For each feature, compute the mean of Average for every category using Pandas.
- Code to show mean:

<img width="681" height="210" alt="image" src="https://github.com/user-attachments/assets/1626ef18-3f12-49a7-882f-10877d0254db" />


OUTPUT:

<img width="349" height="311" alt="image" src="https://github.com/user-attachments/assets/ca639732-1232-4aca-a69f-181566d276f0" />

b. Display the three summary tables.
-Code:

<img width="455" height="47" alt="image" src="https://github.com/user-attachments/assets/22032e6f-7c2a-4ff7-ae0b-2a99486cbaf9" />

c. Create one figure containing three bar charts: mean Average by Track, by Gender, and by
Hometown.
-Code:

<img width="806" height="600" alt="image" src="https://github.com/user-attachments/assets/d5723963-4c41-414c-b119-51309cc1d5bd" />


OUTPUT:

<img width="860" height="260" alt="image" src="https://github.com/user-attachments/assets/3b772025-7a2a-47a6-8d04-f4db2e4ec197" />

d. Below the figure, write three concise statements identifying the category with the highest sample

-Code to show statements with the highest sample per category:

<img width="767" height="154" alt="image" src="https://github.com/user-attachments/assets/4fd1f4da-a311-4cdd-b917-2846bf3fd11c" />


OUTPUT:

<img width="660" height="71" alt="image" src="https://github.com/user-attachments/assets/8715efea-c5fa-48e6-a147-629f54fd5e11" />
