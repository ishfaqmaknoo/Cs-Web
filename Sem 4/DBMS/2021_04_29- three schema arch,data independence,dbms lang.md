## three schema architecture
-----------------------------
1.internal schema

2.conceptual schema

3.External Schema

defines the capture of a database

- 1.define data storage details, when, what?

- - access only to database admin or autherised by admin

- 2.-access of actual data and the realationship

- - access to experienced user

- 3.-give external view specific to end user

comm b/w external schema and conceptual schema is extenal/conceptual mappint

comm b/w internal schema and conceptual schema is conceptual/internal mappint

## data independence
-----------------
abiliity to change the data at a particular level without affecting the other

### 2 types

#### logical data independence
ability to change or modify conceptual schemal without affecting external
level

eg: data retrival and modify

#### physical data independence
ability to change or modify internal schemal without affecting conceptual
schema

eg: change file structure, add indexing 

## DBMS languages
---------------
data definition lang (ddl)

data manipulation lang (dml): - procedural and non procedural dml

### ddl
to specify conceptual schema

ddl used to define internal and external schemas

some dbms have sotrage definition lang used to define internal
and view definition lang to define external

### Data manipulation lang (dml)
to modify data

can be used with high level lang

dml can alternatively be applied as query directly (called a query lang)

## types of dml
------------
### procedural/low lvl
mention the query along with position pointer

only retirve one row at a time

### non procedural dml/high lvl
what data to retrive rather than how to retrive it

also called declarative lang

