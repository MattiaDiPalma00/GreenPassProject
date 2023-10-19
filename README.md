# GreenPassProject

The plan previews the implementation of a service management of the green passes, to the aim to ensure various operations to check the validity of the certificate. A user, after have carried out vaccination, will communicate the code of your health card to the vaccine center via a client. The vaccine center will in turn communicate the data received input to ServerV that will insert them into a database (sqlite) specially created. The clients will communicate the card code to the ServerG health, which has the task of requiring ServerV to check the validity. The ClientT has the privilege of invalidating or restoring the validity of a green pass, depending on the contagion or the healing of a person, communicating to ServerG the code of the health card. For consistent and secure storage of data both of the user and of its certificate we used an external database (sqlite).

For more details : 
* [Relazione Progetto ](https://github.com/MattiaDiPalma00/GreenPassProject/blob/main/Relazione%20Progetto.pdf)

