# ConnectSQLServerToPowerBI

# In this Project I am going to show how to connect SQL Server to Power Bi

/****** Simple SQL Query  ******/

SELECT count(*)  As Total_Aliens

  FROM [test].[dbo].[Aliens$] 
  
# Output:
  
  ![image](https://user-images.githubusercontent.com/16399584/189553596-d06013b6-34f4-4ae3-921c-dcc6ce991b7a.png)

# Oper Power Bi and click On Get Data  :
# Then Click on Database and choose SQL Server Database:

![image](https://user-images.githubusercontent.com/16399584/189553735-ce8a7da7-a68b-4bdf-a2ff-fa80609e4ede.png)

# Then type your Server Name, Database Name 
# Then Copy and Pasete your SQL Code in SQL Statement textbox and  click OK


![image](https://user-images.githubusercontent.com/16399584/189553920-951df413-acb8-41b2-8868-d8c4b609ed08.png)

# Below Window will popup if its connect SQL Server successfully. Then load it into Power BI.

![image](https://user-images.githubusercontent.com/16399584/189554129-6db807fd-86af-435b-a729-3794047cab4f.png)

# After Loading it will appear on right hand side under Field pane as Query1 and its ready to use for Power BI Dashboard

![image](https://user-images.githubusercontent.com/16399584/189554254-33f43c28-b549-45f8-9608-941ef2bb305f.png)





