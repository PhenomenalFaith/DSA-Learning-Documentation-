# DSA-Learning-Documentation-
This repository gives detailed work on my learnings  in Power BI.
## Data Cleaning.
 The whole data cleaning exercise was carried out using the Power BI software, and the data sets used were the following:
* Columnar Data
* Trim and clean.
   * For the columnar data, the initial promoted headers were removed, then the table was transposed, moving the cities from the different rows to a particular column. To fill the null values in the row with cities, we used the Fill Down option. Then we used the first row as a header. After doing that, I selected the first two columns and unpivoted the other columns. Then I renamed the columns and did the sum of the products by groups. This is maximising data performance.
 
   * To clean the Trim and Clean file, in the transform state, the first row was the Username and since it wasn’t really necessary, we used the remove function. The name column had a lot of spaces before and in between. To take care of that, we used the Trim function by selecting the column, right-clicking and selecting Transform, then Trim. This took care of the spaces to the left. The same way was used to get the clean which took away the spaces in between. The replace values was used to take out the excess spacing in the column, and the Name column was finally cleaned.
For the gender, we changed it to Proper case to give a consistent column. An issue was encountered, the Title or the name and the gender didn’t tally. To solve that, the column “Name” was split from the left using the delimiter.  To get the new gender, a conditional column is used to state the condition, which in this case is “If Mr, male; if Mrs, female; if Ms, female; if Dr, Male”.
  * Merge and Append:
Append data means joining a table having the same column heading together. This increases the number of rows.
The dataset Leeds, Liverpool, Manchester were first cleaned, columns renamed and the column (Date paid) was removed from the Manchester data as it wasn’t necessary for the append. This is to make it consistent (4 rows ) with the other datasets to be appended. 
Merging: means extracting a column from a table to add to another table. We merged the personal and general data together taking the blood group, Height and weight from the personal data into the General data table as a new table then renamed it Patient Confidentiality Record. Then we took out the null columns.


<img width="960" alt="Append Steps" src="https://github.com/user-attachments/assets/fc7fd746-5bcb-4507-893e-89666e21f4be" />

<img width="960" alt="Append  end" src="https://github.com/user-attachments/assets/bc8abd0e-69c2-44e7-955b-34adbc68b75f" />







## Data Modelling.


