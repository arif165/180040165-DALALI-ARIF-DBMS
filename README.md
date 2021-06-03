# 180040165-DALALI-ARIF-DBMS


What is ER Diagram?
ER Diagram stands for Entity Relationship Diagram, also known as ERD is a diagram that displays the relationship of entity sets stored in a database. In other words, ER diagrams help to explain the logical structure of databases. ER diagrams are created based on three basic concepts: entities, attributes and relationships.
ER Diagrams contain different symbols that use rectangles to represent entities, ovals to define attributes and diamond shapes to represent relationships.

History of ER models
ER diagrams are a visual tool which is helpful to represent the ER model. It was proposed by Peter Chen in 1971 to create a uniform convention which can be used for relational database and network. He aimed to use an ER model as a conceptual modeling approach.


Why use ER Diagrams?
Here, are prime reasons for using the ER Diagram

Helps you to define terms related to entity relationship modeling
Provide a preview of how all your tables should connect, what fields are going to be on each table
Helps to describe entities, attributes, relationships
ER diagrams are translatable into relational tables which allows you to build databases quickly
ER diagrams can be used by database designers as a blueprint for implementing data in specific software applications
The database designer gains a better understanding of the information to be contained in the database with the help of ERP diagram
ERD Diagram allows you to communicate with the logical structure of the database to users

ER Diagrams Symbols & Notations
Entity Relationship Diagram Symbols & Notations mainly contains three basic symbols which are rectangle, oval and diamond to represent relationships between elements, entities and attributes. There are some sub-elements which are based on main elements in ERD Diagram. ER Diagram is a visual representation of data that describes how data is related to each other using different ERD Symbols and Notations.

Following are the main components and its symbols in ER Diagrams:

Rectangles: This Entity Relationship Diagram symbol represents entity types
Ellipses : Symbol represent attributes
Diamonds: This symbol represents relationship types
Lines: It links attributes to entity types and entity types with other relationship types
Primary key: attributes are underlined
Double Ellipses: Represent multi-valued attributes
ER Diagram Symbols
![image](https://user-images.githubusercontent.com/64208917/120594600-d08fff80-c45e-11eb-9562-cc9db446c367.png)


Components of the ER Diagram
This model is based on three basic concepts:

1.Entities
2.Attributes
3.Relationships

WHAT IS ENTITY?
A real-world thing either living or non-living that is easily recognizable and nonrecognizable. It is anything in the enterprise that is to be represented in our database. It may be a physical thing or simply a fact about the enterprise or an event that happens in the real world.

An entity can be place, person, object, event or a concept, which stores data in the database. The characteristics of entities are must have an attribute, and a unique key. Every entity is made up of some 'attributes' which represent that entity.

Examples of entities:

Person: Employee, Student, Patient
Place: Store, Building
Object: Machine, product, and Car
Event: Sale, Registration, Renewal
Concept: Account, Course

Attributes
It is a single-valued property of either an entity-type or a relationship-type.

For example, a lecture might have attributes: time, date, duration, place, etc.

An attribute in ER Diagram examples, is represented by an Ellipse


Relationship
Relationship is nothing but an association among two or more entities. E.g., Tom works in the Chemistry department.

Simple attribute	Simple attributes can't be divided any further. For example, a student's contact number. It is also called an atomic value.
Composite attribute	It is possible to break down composite attribute. For example, a student's full name may be further divided into first name, second name, and last name.
Derived attribute	This type of attribute does not include in the physical database. However, their values are derived from other attributes present in the database. For example, age should not be stored directly. Instead, it should be derived from the DOB of that employee.
Multivalued attribute	Multivalued attributes can have more than one values. For example, a student can have more than one mobile number, email address, etc.

Cardinality
Defines the numerical attributes of the relationship between two entities or entity sets.

Different types of cardinal relationships are:

One-to-One Relationships
One-to-Many Relationships
May to One Relationships
Many-to-Many Relationships

1.One-to-one:

One entity from entity set X can be associated with at most one entity of entity set Y and vice versa.

Example: One student can register for numerous courses. However, all those courses have a single line back to that one student.
![image](https://user-images.githubusercontent.com/64208917/120594982-56ac4600-c45f-11eb-83b1-83ed49667456.png)


2.One-to-many:

One entity from entity set X can be associated with multiple entities of entity set Y, but an entity from entity set Y can be associated with at least one entity.

For example, one class is consisting of multiple students.
![image](https://user-images.githubusercontent.com/64208917/120595035-688de900-c45f-11eb-99c3-95766f08ac73.png)


3. Many to One

More than one entity from entity set X can be associated with at most one entity of entity set Y. However, an entity from entity set Y may or may not be associated with more than one entity from entity set X.

For example, many students belong to the same class.
![image](https://user-images.githubusercontent.com/64208917/120595054-6d529d00-c45f-11eb-9403-b59a515942ea.png)



4. Many to Many:

One entity from X can be associated with more than one entity from Y and vice versa.

For example, Students as a group are associated with multiple faculty members, and faculty members can be associated with multiple students.
![image](https://user-images.githubusercontent.com/64208917/120595073-72afe780-c45f-11eb-8628-ca8ef95a4bee.png)


Best Practices for Developing Effective ER Diagrams
Here are some best practice or example for Developing Effective ER Diagrams.

Eliminate any redundant entities or relationships
You need to make sure that all your entities and relationships are properly labeled
There may be various valid approaches to an ER diagram. You need to make sure that the ER diagram supports all the data you need to store
You should assure that each entity only appears a single time in the ER diagram
Name every relationship, entity, and attribute are represented on your diagram
Never connect relationships to each other
You should use colors to highlight important portions of the ER diagram

Summary
ER Model in DBMS stands for an Entity-Relationship model
The ER model is a high-level data model diagram
ER diagrams are a visual tool which is helpful to represent the ER model
ER diagrams in DBMS are blueprint of a database
Entity relationship diagram DBMS displays the relationships of entity set stored in a database
ER diagrams help you to define terms related to entity relationship modeling
ER Model in DBMS is based on three basic concepts: Entities, Attributes & Relationships
An entity can be place, person, object, event or a concept, which stores data in the database (DBMS)
Relationship is nothing but an association among two or more entities
A weak entity is a type of entity which doesn't have its key attribute
It is a single-valued property of either an entity-type or a relationship-type
It helps you to defines the numerical attributes of the relationship between two entities or entity sets
ER- Diagram DBMS is a visual representation of data that describe how data is related to each other
While Drawing ER diagrams in DBMS, you need to make sure all your entities and relationships are properly labeled.

