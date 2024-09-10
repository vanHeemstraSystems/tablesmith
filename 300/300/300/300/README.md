# 300 - Step 3: Create Stages

Now that Tablesmith knows the columns, we can go to the **Stages** tab to create some real automations. 

Click **Add stage** to create a new one. 

![create_a_new_pipeline-007](https://github.com/user-attachments/assets/2ae3e253-b3d5-470a-b3b3-c633e6cfd88d)

You will see a screen like this:

![create_a_new_pipeline-008](https://github.com/user-attachments/assets/2145bad1-c56f-4bd9-a0e7-655f2386774d)

Both name and description are optional. If you don't input a name, the stage type will be used (here: Sort). 

For convenience we have named the stage **Sort** with a description **Sort by Track Popularity (descending)**.

![create_a_new_pipeline-009](https://github.com/user-attachments/assets/d73aca39-1b7c-4d9f-bd84-93f63b71fe7f)

Click **Select stage type** to see the six stage types supported by Tablesmith: **Filter**, **Sort**, **Add Column**, **Update Column**, **Group**, and **Data Extraction**.

![create_a_new_pipeline-010](https://github.com/user-attachments/assets/0b58aed3-3a65-48d6-888b-95de6e62a80b)

The first four types are very intuitive, the names already tell what they can do. The last two are a little special.

The **Group** stage offers three powerful modes for data manipulation:

1) **Aggregation**: This mode applies a chosen function (like **sum**, **average**, **count**) to ech group, resulting in a single row for each group with the calculated value.

2) **TopN**: This mode retrieves the first ```n``` rows from each group, often used in combination with a **sort** stage.

3) **Expand**: This mode adds ```n``` additional rows to each group, useful for replicating data within groups.

**Data Extraction** is used to extract information from one column in ech row and fill them into one or multiple other columns. Note that this is not for parsing a text/PDF file into a spreadsheet; it runs row by row using Artificial Intelligence (AI), so you need to log in and have tokens.

Our goal is to group by playlist genre and get the top 10 tracks in each group. So we need two stages: **Sort** and **Group (TopN)**.

## 100 - Create the First Stage (Sort)

See [README.md](./100/README.md)

## 200 - Create the Second Stage (Group - TopN)

See [README.md](./200/README.md)

## 300 - Define the Output

See [README.md](./300/README.md)

## 400 - Run the Pipeline

See [README.md](./400/README.md)

MORE
