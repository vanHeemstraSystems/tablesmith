# 300 - Define the Output

In the **Output** tab, specify the output files.

![create_a_new_pipeline-023](https://github.com/user-attachments/assets/2cc53263-d57f-4c61-91e6-8fb4d10096a7)
 
Tablesmith will create new files without altering your original data. You can output multiple files, or sheets in one XLSX file, and choose different columns, reorder columns, or format number/date columns.

To meet our goal of creating an XLSX file with separate sheets for each gere, here's what you can do:

1. Click **Add output**.

![create_a_new_pipeline-024](https://github.com/user-attachments/assets/0c4d3b6f-703b-441c-be4b-740ce0a84738)

2. Enter the filename (here: ```output```) and change the format to XLSX.

3. Keep the source table as **Main**.

![create_a_new_pipeline-025](https://github.com/user-attachments/assets/8eeb9475-fbd9-4924-b84d-c0812702bdb1)

Now the exciting part: the **Sheet name** field. By default, it is set to ```Sheet1```, which isn't what we want. We need the sheet names to be dynamic, reflecting the values in the ```playlist_genre``` column. To achieve this, we'll enable formulas in the Sheet name field. Simply delete ```Sheet1``` and type an ```=``` to activate the formula editor.

![create_a_new_pipeline-026](https://github.com/user-attachments/assets/27f0e22a-4b57-434f-8260-7128c544f629)

4. Use the ```playlist_genre``` column value as the Sheet name by choosing ```playlist_genre``` column in the formula editor.

![create_a_new_pipeline-027](https://github.com/user-attachments/assets/5b8728fb-eabe-42dd-96c5-d7806b252218)

5. **Save** and close the formula editor.



7. Click **Save** again to finish creating this output.

MORE
