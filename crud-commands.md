# CRUD Commands

- [panel::crud](#crud)
- [panel::createmodel](#createmodel)
- [panel::createcontroller](#createcontroller)

<a name="crud"></a>
## panel::crud

To create a CRUD automatically, you should run the following command :

	php artisan panel:crud <entity-name>

This command creates the model and controller of an entity. Before running this command, you should create the table. But if you want to create the CRUD manually, you can run the following commands to create the model and the controller.

Note that after running the CRUD command and creating the corresponding table, you'll see the entity name listed in the left sidebar of the panel but when you click on it you'll see a blank output so you need to edit the corresponding controller and add the required fields for your CRUD.

<a name="createmodel"></a>
## panel::createmodel

To create the model of an entity, you should run the following command :

	php artisan panel:createmodel <entity-name>

<a name="createcontroller"></a>
## panel::createcontroller

To create the controller of an entity, you should run the following command :

	php artisan panel:createcontroller <entity-name>

## create migration for your crud
[Read from laravel document](http://laravel.com/docs/5.1/migrations) 


[>Next (Add your fileds to crud controller you have created)](crud-fields) 
