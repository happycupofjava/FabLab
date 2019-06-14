# FabLab
Documentation for the modules implemented at FabLab.
(1) Module 1
Purpose: Doumentation for the Offline Mode implemented at FabLab that provides the FabLab services even with the Servers are down to increase system availability.

Technologies Used: Front-end: HTML, CSS, JavaScript and Knockout JS.

APIs: FLASK APIs to query the status of the Database to check if the system is online or offline.

Storage: JSON files to hold the user data and log the transaction data when working in offline mode.

(2) Module 2
Problem Statement: The transaction id generated for each print job(Online/Offline) was difficult to retreive and present on the User Interface using AJAX and jQuery.

Approcach: Using the metadata information that created the transaction id.

Technologies used: Python2.7, Knockout JS, HTML, CSS.
