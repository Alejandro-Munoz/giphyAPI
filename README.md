# Giphy app

## What is it?
A fun app that allow to request and show funny gifs, build with Bootstrap, jQuery and Ajax.

The application provides 3 main sections:

	* List of Animals
	* Add Animal
	* Results

Refer to the [**Show Me**](#show-me) section below for examples on how to use each of the views.

## How do I use it?

Clone this repository.

Then, open in browser:

`index.html`

## Show Me

After opening `index.html` in browser, you will be presented with the app home page.

![giphy_index](images/for_readme/giphy_index.png)

## List of Animals

In this section you will find a list of buttons which you can click and the app will make an api request to retrieve gifs relative to button text animal.

![list_of_animals](images/for_readme/list_of_animals.png)

After clicking in an animal button the app will present you a list of static gifs in the Results section.

![giphy_results](images/for_readme/giphy_results.png)

You can also click on each animal gif to make them MOVE!!!.

### Invalid Input Handling

During order processing, if an invalid item ID/quantity value is provided, you will not be allowed to proceed until a valid item ID/quantity is entered.

![invalid item id](images/for_readme/customer_invalidID.png)

![invalid quantity](images/for_readme/customer_invalidInventoryAmount.png)

If the store does not have enough quanity on hand, the order will not be processed.

![not enough quantity](images/for_readme/customer_notEnoughInventory.png)

## Manager View

The Manager View provides you with the following choices.

![manager choices](images/for_readme/manager_choices.png)

### View Products for Sale

Provides you with a table of the current items for sale in the store.

![manager products for sale](images/for_readme/manager_viewProducts.png)

### View Low Inventory

Provides you with a table of the current items in the store with a quanity less than 5.

![manager low inventory](images/for_readme/manager_lowInventory.png)

### Add to Inventory

Provides you with the ability to add inventory to a currently existing item ID.

![manager add to inventory](images/for_readme/manager_addToInventoryItemId.png)

You will then be prompted to add the amount of inventory to add.

![manager add to inventory](images/for_readme/manager_addToInventory.png)

In the manager view, you will also be able to add a new products to the store.

![manager add product](images/for_readme/manager_addNewProduct.png)

### Invalid Input Handling

In the ** Add to Inventory ** view, if an attempt is made to update an item ID which does not exists, you will be presented with an error.

![add to inventory invalid id](images/for_readme/manager_addToInventoryError.png)

## Supervisor View

The Supervisor view allows you the following options.

![supervisor choices](images/for_readme/supervisor_choices.png)

### View Product Sales by Department

Provides you with a table of the total sales by available departments.

![supervisor total sales](images/for_readme/supervisor_viewProductSales.png)

### Create Department

Allows you to create a new department.

![supervisor create dept](images/for_readme/supervisor_createDepartment.png)
