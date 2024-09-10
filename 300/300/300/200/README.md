# 200 - Step 2: Define the Input

Since we want to group by genre and sort by popularity, we need to specify these columns.

This is done in the **Input** tab.

Here you can add the columns that will be used in the stages or exported in the output files. Here, you also need to specify the data type for each column as tablesmith works with typed data.

Different stages may have specific configurations depending on the data type of the column used.

If your spreadsheet is a well-formatted table, these columns should be the first row (often called the Header Row) and you can simply load them directly from a file.

However, if you don't have the file but understand the data structure (schema), you can also add them manually.

We use the file that is in this repository at ```data/csv_ms_dos.csv```, hence we click **Load columns from file```:



