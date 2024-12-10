![Tec de Monterrey](images/logotecmty.png)
# Act 2.1 - Team Implementation of a Linear Data Structure ADT

## <span style="color: rgb(26, 99, 169);">What Do I Have to Do?</span>
In this repository, you will find the file "list.h," which you must modify to develop this activity. At the top of the file, include your personal information in comments. For example:
```
// =========================================================
// File: list.h
// Author: Edward Elric - A00123456
// Date: 01/01/2021
// =========================================================
```


Individually design and implement, following the interface specification, an ADT that represents a linear data structure:

Depending on the linear data structure ADT, you must implement CRUD (Create, Read, Update, Delete) operations for elements in the data structure. Some operations may not apply to certain data structures.

<table style="border-collapse: collapse; border: 1px solid;">
<thead>
<tr style="background-color: rgb(25, 99, 169);">
<th style="color: white;" rowspan="5">insert_at (create)</th>
<th>Description</th>
<th>Adds an element at *index* (0 <= *index* <= *size*). The element previously at that position is shifted to the right.</th>
</tr>
<tr>
<th>Input</th>
<th>*val*, the value to be inserted, and *index*, the position where it will be inserted.</th>
</tr>
<tr>
<th>Output</th>
<th>Valid data structure showing the insertion of the element. If the position is invalid, an exception must be thrown.</th>
</tr>
<tr>
<th>Precondition</th>
<th>A valid structure.</th>
</tr>
<tr>
<th>Postcondition</th>
<th>Modified structure.</th>
</tr>
</thead>
</table>

<br>

<table style="border-collapse: collapse; border: 1px solid;">
<thead>
<tr style="background-color: rgb(25, 99, 169);">
<th style="color: white;" rowspan="5">get (read)</th>
<th>Description</th>
<th>Returns the element at the position specified by *index* (0 <= *index* < *size*).</th>
</tr>
<tr>
<th>Input</th>
<th>The position, *index*, of the required element.</th>
</tr>
<tr>
<th>Output</th>
<th>The element at the specified position. If the position is invalid, an exception must be thrown.</th>
</tr>
<tr>
<th>Precondition</th>
<th>A valid structure.</th>
</tr>
<tr>
<th>Postcondition</th>
<th>None.</th>
</tr>
</thead>
</table>

<br>

<table style="border-collapse: collapse; border: 1px solid;">
<thead>
<tr style="background-color: rgb(25, 99, 169);">
<th style="color: white;" rowspan="5">indexOf</th>
<th>Description</th>
<th>Returns the position of the element *val*.</th>
</tr>
<tr>
<th>Input</th>
<th>The element to search for.</th>
</tr>
<tr>
<th>Output</th>
<th>The position of the searched element. If the element is not found, returns -1.</th>
</tr>
<tr>
<th>Precondition</th>
<th>A valid data structure.</th>
</tr>
<tr>
<th>Postcondition</th>
<th>None.</th>
</tr>
</thead>
</table>

<br>

<table style="border-collapse: collapse; border: 1px solid;">
<thead>
<tr style="background-color: rgb(25, 99, 169);">
<th style="color: white;" rowspan="5">remove_at (del)</th>
<th>Description</th>
<th>Removes the element at *index* (0 <= *index* < *size*).</th>
</tr>
<tr>
<th>Input</th>
<th>The position, *index*, of the element to remove.</th>
</tr>
<tr>
<th>Output</th>
<th>The element at the specified position. If the position is invalid, an exception must be thrown.</th>
</tr>
<tr>
<th>Precondition</th>
<th>A valid data structure.</th>
</tr>
<tr>
<th>Postcondition</th>
<th>Properly updated data structure.</th>
</tr>
</thead>
</table>

<br>
All functionalities must be correctly aligned and documented. Additionally, all functionalities must pass all tests successfully. As part of the documentation, include the complexity of each functionality.

To test your implementation, execute the command:
```
make
```
This command will compile your code and generate a series of test files called "runTest#", where # is the test number. To execute a test, run the appropriate file. For example, to check if your code meets test number 3, you should run:
```
./runTest3
```

## <span style="color: rgb(26, 99, 169);">**How Is My Evidence Evaluated?**</span>

- **80%** - For each functionality, the evaluation will be:
    - **Excellent (80%)** - correctly passes all test cases.
    - **Very Good (60%)** - correctly passes 75% of test cases.
    - **Good (40%)** - correctly passes 50% of test cases.
    - **Insufficient (20%)** - correctly passes less than 50% of test cases.

- **10%** - The code must follow the coding standards specified in the document: <span class="instructure_file_holder link_holder">[coding_standard_link](estandar.pdf)</span>.
- **10%** - Function names in the application must be respected.

## <span style="color: rgb(26, 99, 169);">**How Do I Submit It?**</span>
Create a ZIP file of your repository. Ensure that all necessary files are included.

## <span style="color: rgb(26, 99, 169);">**Where Do I Submit It?**</span>
Upload the file in the space provided for this activity on Canvas.
