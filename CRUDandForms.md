# Working with forms
##  work with HTML Forms in Django.
###  the easiest way to write forms to create, update, and delete model instances. 
### An HTML Form is a group of one or more fields/widgets on a web page, which can be used to collect information from users for submission to a server.
###  Forms are a flexible mechanism for collecting user input because there are suitable widgets for entering many different types of data, including text boxes, checkboxes, radio buttons, date pickers and so on.
- [x] The submit input will be displayed as a button (by default) that can be pressed by the user to upload the data in all the other input elements in the form to the server .
- [x] The form attributes define the HTTP method used to send the data and the destination of the data on the server (action):
- [x]  action: The resource/URL where data is to be sent for processing when the form is submitted.
- [x]  If this is not set (or set to an empty string), then the form will be submitted back to the current page URL.
- [x]  method: The HTTP method used to send the data: post or get.
- [x]  The POST method should always be used if the data is going to result in a change to the server's database because this can be made more resistant to cross-site forgery request attacks.
- [x]  The GET method should only be used for forms that don't change user data (e.g. a search form).

##  URL configuration
## Before we create our view,  add a URL configuration for the renew-books page. 
### Copy the configuration to the bottom of locallibrary/catalog/urls.py.
### The URL configuration will redirect URLs with the format /catalog/book/<bookinstance_id>/renew/ to the function named renew_book_librarian() in views.py,
### And send the BookInstance id as the parameter named pk.
###  The pattern only matches if pk is a correctly formatted uuid.

## View
- [x] the view has to render the default form when it is first called and then either re-render it with error messages if the data is invalid, or process the data and redirect to a new page if the data is valid.
- [x] In order to perform these different actions, the view has to be able to know whether it is being called for the first time to render the default form, or a subsequent time to validate data.
## ModelForms
- [x]  Creating a Form class using the approach described above is very flexible, allowing you to create whatever sort of form page you like and associate it with any model or models.

- [x] Tf  need a form to map the fields of a single model then your model will already define most of the information that you need in your form: fields, labels.