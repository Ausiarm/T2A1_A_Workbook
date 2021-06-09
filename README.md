 # <div align="center"> T2A1_A_Workbook </div>

## Q1 Architecture of a Rails Application
- The architecture of a typical rails application can be effectively described as a combination of the MVC architecture pattern infused with the convention over configuration or coding by convention standards. These convention standards allow for the developer to functionally bypass the setup processes of creation of an app by agreeing to a universal formatting that allows businesses to interact with one another by creating standards of codebases and presentation of files. In the MVC architecture pattern, code for an application is broken up into three constituent elements: 
    1. Model: The model both represents and manages the content/data in an application as well as defines the data structure and relationships of that content. In addition, it connects to the database and can retrieve and modify content while processing some validation of the data.
    2. View: the view is the part of the application that the user interacts with, it is the part of the application that will display the models' data once it is passed over by the controller. 
    3. Controller: as its name indicates, the controller is the part of a rails application that handles changeover and the job of connecting the model as the source of data with the view. This is then conveyed to the browser as the user endpoint of interaction with that data. When the user attempts to interact with data in the form of browser interaction it must be processed and passed through the controller before any data manipulation in the model can occur. 

- [Source](https://ait.instructure.com/courses/3520/pages/mvc?module_item_id=272763)

## Q2 Pros and Cons of a Commonly Used DBMS
- Identify a database management system (DBMS) commonly used in web applications (including Rails) and discuss the pros and cons of this database
- PostgreSQL is one of a few of the larger and more commonly used DBMS's in the commercial sphere. 
    - advantages: 
      - Open source: unlike other large DBMS on the market, PostgreSQL is open source and free to the public. 
      - It is supported across many platforms including mac, windows, and linux. This is beneficial as it means that it can be used and successively tested in multiple environments making PostgreSQL more robust and applicable accross the different environments supported in the commercial sphere. 
      - Its status as open source means that it has a constant source of user testing it which leads to regular updates, making it incredibly robust and long lived. 
      - It is known in industry as being one of the most secure DBMS's for data integrity. 
      - Specifically, as far as rails is concerned, it is the industry standard as far as DBMS is concerned even though rails natively includes SQLlite.
    - Disadvantages:
      - Unfotunately, given that it is open source and not controlled by a single entitiy, it has a hard time keeping pace with other DBMS's such as MySQL or Oracle's DBMS due to their controlled ability to pivot in relation to industry changes. 
      - Due to its advantage of being highly compatible among many different languages, PostgreSQL loses out in relation to enhanced speed improvements when compared to something like MySQL which openly accepts its incompatability as a tradeoff for focusing on building a faster DBMS into the future. 
      - 

## Q3 Implementation of Agile Methodology in Projects
- Discuss the implementation of Agile project management methodology

## Q4 Source Control Workflow Overview and Description
- Provide an overview and description of a standard source control workflow

## Q5 Standard Software Testing Process Overview and description
- Provide an overview and description of a standard software testing process (e.g. manual testing)

## Q6 Information System Security Discussion and Analysis
- Discuss and analyse requirements related to information system security and how they relate to the project

## Q7 Information and Data Protection Methods
- Discuss common methods of protecting information and data and how you would apply them to the project

## Q8 Legality in Relation to User Data
- Research what your legal obligations are in relation to handling user data and how they can be met for the project

## Q9 Relationship Database Model Structural Aspects
- Describe the structural aspects of the relational database model. Your description should include information about the structure in which data is stored and how relations are represented in that structure.

## Q10 Relationship Database Model Integrity Aspects
- Describe the integrity aspects of the relational database model. Your description should include information about the types of data integrity and how they can be enforced in a relational database.

## Q11 Relationship Database Model Manipulative Aspects
- Describe the manipulative aspects of the relational database model. Your description should include information about the ways in which data is manipulated (added, removed, changed, and retrieved) in a relational database.

## Q12 Marketplace Website Application Research
- Conduct research into a marketplace website (app) and answer the following parts:  a. List and describe the software used by the app.
  b. Describe the hardware used to host the app.
  c. Describe the interaction of technologies within the app
  d. Describe the way data is structured within the app
  e. Identify entities which must be tracked by the app
  f. Identify the relationships and associations between the entities you have identified in part (e)
  g. Design a schema using an Entity Relationship Diagram (ERD) appropriate for the database of this website (assuming a relational database model)