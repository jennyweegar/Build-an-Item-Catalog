# Build-and-Item-Catalog

This is project #4 for Udacity's Full Stack Web Developer Nanodegree. Here I created a web applicaiton that provides a list of items with many differnet catagories for a restaurant menu. The web application also has a user registration and authentication system. Once registered, users will have the ability to post, edit and delete their items.

## Features
Login to create edit and delet items on the restaurant menu <br>
Publicly view all items and catagories from the database

## Requirments
Google developer account: https://developers.google.com/ <br>
Python 3: https://www.python.org/downloads/ <br>
Vagrant: https://www.vagrantup.com/downloads.html <br>
Viewbox: https://www.virtualbox.org/wiki/Download_Old_Builds_5_1 <br>

## How to run this program <br>
You will need to download all materials listed above. Once downloaded clone this repository to your machine nd unzip the files. Launch Vagrant VM by running ```vagrant up``` in your terminal (this may take quite a long time to run) and then logon to Vagrant with ```vagrant ssh```.

Change directories to ItemCatalog ```cd /vagrant/ItemCatalog```. [Run ```DBsetup``` to create a database. Run ```addItems.py``` to add example items and categories]

Run ```webserver.py``` and access the results at http://localhost:8000

You can exit the application by pressing 'ctrl+c' in your terminal.



