# Build-and-Item-Catalog

This is project #4 for Udacity's Full Stack Web Developer Nanodegree. Here I created a web application that provides a list of restaurants with many different categories and items listed for a restaurant menu. You can see all the restaurants form the main page, you can then click on different restaurants and see the menu for each one. The web application also has a user registration and authentication system. Once registered, users will have the ability to post, edit and delete their own menu items under every category.

## Features
Login to create edit and delete items on the restaurant menu <br>
Publicly view all items and categories from the database

## Requirments
Google developer account: https://developers.google.com/ <br>
Python 3: https://www.python.org/downloads/ <br>
Vagrant: https://www.vagrantup.com/downloads.html <br>
Viewbox: https://www.virtualbox.org/wiki/Download_Old_Builds_5_1 <br>

## How to run this program <br>
You will need to download all materials listed above. Once downloaded clone this repository to your machine nd unzip the files. Launch Vagrant VM by running ```vagrant up``` in your terminal (this may take quite a long time to run) and then logon to Vagrant with ```vagrant ssh```.

Change directories to ItemCatalog ```cd /vagrant/ItemCatalog```. [Run ```database_setup.py``` to create a database. Run ```lostofmenus.py``` to add example items and categories]

Run ```project.py``` and access the results at http://localhost:5000

You can exit the application by pressing 'ctrl+c' in your terminal.



