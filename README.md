# Inventory Management System

*"Simple Inventory Management System powered by Flask"*

## Table of Contents

  - [Installation](#installation)
  - [Overview](#overview)
  - [Usage](#usage)
    - [Starting Things Up](#starting-things-up)
    - [Getting Into It](#getting-into-it)
        - [Inserting products and locations](#adding-products-and-locations)
        - [Moving things around](#moving-things-around)
        - [Editing Existing Data](#editing-existing-information)
  - [Dependencies](requirements.txt)
  - [License](#license)

## Installation

Clone the git
repository:

``` sourceCode console
$ git clone https://github.com/akshanshbhatt/Army-Base-Camp-Project-2.git
$ cd Army-Base-Camp-Project-2
```
![](docs/util/1.gif)

Install necessary dependencies

``` sourceCode console
$ pip install -r requirements.txt
```

which is actually the same as

``` sourceCode console
$ pip install flask
```
![](docs/util/2.gif)


## Overview

The _index page_ or _summary_ covers the summary of the system containing lists of products and location along with a count of unallocated products.
On the _products page_, we can add/edit/remove products from the system. The _location page_ covers similar functionality in the context of locations or warehouses.
On the _logistics  page_, movement of products can be performed. It also maintains the history of all transactions in a tabular form.

## Usage

### Starting Things Up

To run the application, change the current working directory to
\~/Army-Base-Camp-Project-2/

``` sourceCode console
$ cd inventory
```

run the app by typing the following command in your terminal

``` sourceCode console
$ python -m flask run
```

![](docs/util/3.gif)

The application can be accessed at _localhost:5000_ in your browser

![](docs/util/4.gif)

This view of the system can be accessed for demo purposes on installation, to start afresh remove thr inventory.sqlite file from the parent folder

![](docs/util/5.gif)

### Getting Into It

A new system will look like this

![](docs/util/6.gif)

#### Adding Products and Locations

To add products, only the name and quantity are required
Adding locations needs only the name to be added

![](docs/util/7.gif)

#### Moving Things Around

Products can be moved into and between warehouses *only after* they have been added to the system

![](docs/util/8.gif)

Moving into locations

![](docs/util/9.gif)

Moving between locations

#### Editing Existing Information

Editing Product Information

![](docs/util/10.gif)

Editing Location Information

![](docs/util/11.gif)

Deleting Products and Locations on the System

![](docs/util/12.gif)


## Dependencies

  - Just Flask\!

## License

This code has been released under the [MIT License](LICENSE).

## How to serve on your local

1. open this folder in vscode
2. create a virtual env if u want ( "python -m venv env" enter this in terminal )
3. activate it by env/scripts/activate in terminal
4. select python interpreter
5. install flask
6. cd inventory/
7. run it by "$env:FLASK_APP="app" in terminal
8. "flask run" in terminal
9. goto localhost
