# :dart: Snowflake_DataLoading & Analysis
### :small_orange_diamond: This repository contains scripts and information for loading data into Snowflake
###   a cloud-based data warehousing platform.
### The basic steps to load local data into snowflake:
1.Check the input source type of your Dataset.

2.Create & Run target table SQL Command.

3.Select database, schema and table

4.Load data into table

#### After we have the source input, let us check the data first:
<img width="959" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/8b214f6b-d3a6-4965-93b2-e1b312419178">

💠 We should notice that there is a redundant header in the first line we will not use it. Also, the data format needs to be processed carefully, as there is no second suffix. The comma in a inner sentence should be isolated, it is not a delimiter anymore. All these works need to be done before we load data to table of database.

💠 The next step is to create the target table to Snowflake. We need to choose which one database and schema we want to upload. The constraints can be roughly used:

 <img width="954" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/473143f8-fc62-470d-ba0b-237f3a212bc7">

 We can see the Empty Table has been created on your selected Database and schema


💠 Now we have to Load Data Into the Table : 
<img width="951" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/7b96945b-861b-452c-b005-c61fbb1d25fa">


💠 Browse your dataset file :
<img width="955" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/c512d3d3-11aa-40cb-8a9e-caa9c50a27e6">

💠 After selecting your file click on next:
<img width="960" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/82723817-7116-4311-bb83-bc00262cd7d1">

💠 Select your File Formate, Header, Field optionally enclosed by, and other :
<img width="959" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/b037b8ed-b935-454d-8ab3-6b693159462e">

💠 See Data Preview:
<img width="960" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/fa47d994-a2e2-4a9b-bc29-9dbaac7c3dba">

💠 We can also use sql queries to check data using < Select * from > :
<img width="957" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/53774500-be57-4def-999d-90a6f172d01f">

✅ That's All. We managed to load the data from the local to Snowflake.

📊 We can also do Analysis of our Data using snowflake charts and filters:
<img width="960" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/332ed45c-9af2-4d79-b1aa-d89f283e7aa2">

<img width="956" alt="image" src="https://github.com/SRUSHTI2493/Snowflake_DataLoading/assets/87080882/8d4706a9-8b42-4b98-92ef-d370e27cec07">











