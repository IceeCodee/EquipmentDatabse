# EquipmentDatabase
The purpose of this repository is to design and create a database to hold information of specific helmet equipment choices for football players

## Tools
* Microsoft SQL Server used to store data
* Google diagrams used to create ERD diagram
* Python, Tkinter used to create a GUI inorder to streamline the data entry process

## Files
* EquipmentDBCreation.sql --> script to create the equipment database
* EquipmentProject.xlsx --> file that contains the information to be loaded into the database
* Equipment_ERD.png --> picture of my ERD diagram
* GUI.png --> picture of the GUI
* GUI.py --> python script for GUI
* Scripts_for_GUI.sql --> database script for GUI


## Methodology
### Database Design
The Equipment Database was designed as a relational database. It includes 12 tables which are described in more depth in **data dictionaries section**. 

### ERD Diagram
![](Equipment_ERD.png)

### Data Dictionaries 
**Table Name: Brand**

|Field Name | Data Type | Constraint | Description | Example|
|-----------|-----------|------------|-------------|--------|
| BrandID | INT | Primary Key | unique identifier for each brand | 1 |
