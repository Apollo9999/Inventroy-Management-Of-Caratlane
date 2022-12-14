# Inventroy-Management-Of-Caratlane

A mobile application that is capable of having all the details of the equipment like S/N, Date of Installation etc. by scanning a QR code/ barcode and Readily access the past service record.



Features of the applications :

* QR code generator-based inventory control system.

By using QR Code generator workers and Admin need not manage the inventory control register. They can fill the details of the inventories and generate a QR code. Which can further update by scanning it. Again, this could help them instead managing the register. 
* Reports Fake QR codes by rejecting ID data.

It can detect Fake QR code by rejecting its ID and leading back to the main dashboard.
* Location of Inventory.

Worker and Admin need not write a location on an inventory register they can find it by Google Map.
* Regular notification of inventory services

The worker need not remember the date and month for servicing. The app will automatically remind it by using PUSHBOT Feature.
* Any time  Secure Database

We have our own database server where details of inventories, chat, Images and call are stored.
* Inventory history by scanning QR or typing inventory ID.

Worker or Admin can revisit the inventory and check the history of servicing by scanning a QR code after and before the maintenance.  
* Group Chat (Text, Image and Video calls) Feature with Admin and Worker. 

Admin and worker can chat about the inventory and for next servicing. Safe and Secure Group Chat. Their chat will be secured and no one can copy it.

<br>


## Tools used
* Database - Firebase

<br>

## Steps to run

* Fork the repository

* Clone the repository  
  `git clone https://github.com/Apollo9999/Inventroy-Management-Of-Caratlane.git`   



## Contributions 

* Contributors are welcome and please comment on the issue before working on it.
* Create pull requests, submit bugs, suggest new features.
* Join the Gitter Channel for queries and other related stuff.
* Add your app to firebase. The steps can be found [here](https://firebase.google.com/docs/database/android/start)
* In the second step you will be prompted to download ```google-services.json```. Replace the ```google-services.json``` in the current directory with the new downloaded file. 

The main objective of the project is to create for each store of Caratlane, we have a different amount of inventory. 
And all ou rinventory is recorded in our system. In this system, we have the product image,bar code, price, and 
other information related to an available product. In the store, we have the physical product along with their barcode tags and SKUcodes.
Whenever a sale happens, the sold product is archived from the system.Now the issue is, we do not have a register 
(or such) for where the product is located in the store room. Which rack and which row of which rack? Stock 
Reconciliation, which is whether the inventory that is mentioned in the system is present in the store as well. It's a 
manual and long process that we do every day to ensure all the products are available.
Problems to be addressed are mentioned as follows :-
1. Smart counting of stocks and verifying it against the system,
2. Automatic identification of the availability of a particular piece/item against the racks in our physical store
