# DOCUMENTATION 

This is an example of the documentation of a service which contains the basic functions for managing a resource, CRUD.
It also allows the production of html extension documentation from the main file in Yml

## STRUCTURE
````
service.yml
components
    parameters
        parameters.yml
    responses
        responses.yml
    schemas
        models
            models.yml
        payloads
            payload.yml
        responses.yml
            error.yml
            successful.yml
examples
    books.json

README.md
package.json
````

## COMPONENTS
#### Parameters
> It contains all the parameters that will be used in the requestbody

#### Responses
> It contains all the answers that will be obtained after the end of the request

#### Schemas
> It contains all the schemes that will be reused

----

## WARNING
Do not change the name of the main file : Service.yml


## HOW TO USE 

Modify the content of the service file according to your needs

* Using the ``` npm install ``` command to install dependency
* Using the ``` npm start ``` command to generate html documentation

