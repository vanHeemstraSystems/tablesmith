# 200 - Create the Second Stage (Group - TopN)

Click **Add stage**.

![create_a_new_pipeline-015](https://github.com/user-attachments/assets/a7edf41e-1e88-42ca-b5a9-ca3545e65847)

Name the stage **Group** and give a description **Group by Genre (TopN)**.

![create_a_new_pipeline-016](https://github.com/user-attachments/assets/814b5a40-5bc4-42cd-95e0-ea4b98bd60e9)

Click **Select stage type**.

![create_a_new_pipeline-017](https://github.com/user-attachments/assets/5a35bc0a-598a-4766-988d-f66ac8d3afe7)

Select the **Group** stage type.

![create_a_new_pipeline-018](https://github.com/user-attachments/assets/55231cc6-d27d-4fd0-9faf-faa4c6a62dec)

Change the mode to **TopN**.

![create_a_new_pipeline-019](https://github.com/user-attachments/assets/88aa5037-6b04-450a-9d3f-988a9cd7b4c6)

Click **Add group column** and select ```playlist_genre```.

![create_a_new_pipeline-020](https://github.com/user-attachments/assets/ba929f30-6684-41b3-a450-41beacff1098)

Set the **Limit** to 10 (for the top 10 tracks).

![create_a_new_pipeline-021](https://github.com/user-attachments/assets/7300a778-0a5d-4df7-b2b0-132678dedab1)

Click **Save**

![create_a_new_pipeline-022](https://github.com/user-attachments/assets/b72f13c7-3dbe-48b1-894b-e72cb790fe40)
