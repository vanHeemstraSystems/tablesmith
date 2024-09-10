# 200 - Step 2: Define the Input

Since we want to group by genre and sort by popularity, we need to specify these columns.

This is done in the **Input** tab.

Here you can add the columns that will be used in the stages or exported in the output files. Here, you also need to specify the data type for each column as tablesmith works with typed data.

Different stages may have specific configurations depending on the data type of the column used.

If your spreadsheet is a well-formatted table, these columns should be the first row (often called the Header Row) and you can simply load them directly from a file.

However, if you don't have the file but understand the data structure (schema), you can also add them manually.

We use the file that is in this repository at ```data/csv_ms_dos.csv```, hence we click **Load columns from file```:

![create_a_new_pipeline-004](https://github.com/user-attachments/assets/e34d85d6-0f7f-4623-9876-c8161ab54259)

Select the file ```tracks_ms_dos.csv``` and click **Open**.

![create_a_new_pipeline-005](https://github.com/user-attachments/assets/5dd06862-7db7-432e-a100-51156c1b9ab8)

You will be prompted as above, but as the first in the csv file contains indeed the column names, we can continue by clicking **Done**.

Tablesmith has uploaded the column names correctly and figured out their data types (probably based on the values for each column in the csv file).

![create_a_new_pipeline-006](https://github.com/user-attachments/assets/b4eec368-0ced-4021-a452-5f62a5279b27)
