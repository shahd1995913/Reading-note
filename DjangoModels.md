# Django Models : Using models
##  Django web applications access and manage data through Python objects referred to as models.

### -  Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms, etc.
###  - The definition of the model is independent of the underlying database 
###  - you can choose one of several as part of your project settings. 

###  - Once you've chosen what database you want to use, you don't need to talk to it directly at all.
###  -  you just write your model structure and other code, and Django handles all the dirty work of communicating with the database for you.
## Designing the LocalLibrary models

- [x] When designing your models it makes sense to have separate models for every "object" (a group of related information).
- [x]  In this case, the obvious objects are books, book instances, and authors.
- [x] You might also want to use models to represent selection-list options (e.g. like a drop down list of choices), rather than hard coding the choices into the website itself.
- [x] this is recommended when all the options aren't known up front or may change.
- [x]  Django allows you to define relationships that are one to one (OneToOneField), one to many (ForeignKey) and many to many (ManyToManyField).

## Model primer :  how a model is defined and some of the more important fields and field arguments.

### Model definition
- [x] Models are usually defined in an application's models.py file. They are implemented as subclasses of django.db.models.Model, and can include fields, methods and metadata. The code fragment below shows a "typical" model, named MyModelName.

### Fields
- [x]  A model can have an arbitrary number of fields, of any type — each one represents a column of data that we want to store in one of our database tables.
- [x]  Each database record (row) will consist of one of each field value.
