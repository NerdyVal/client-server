<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> </head> <body> <h1>Client-Server Application for Biological Laboratory</h1> <p> This is a client-server application designed to facilitate the work of a biological laboratory. The application provides the ability to manage the recording of laboratory technicians for a certain type of equipment. </p> 
<h2>Project architecture</h2> <ul> <p> A database that stores a list of users and equipment with a linked schedule.</p> 
  <p>A server application that processes requests from clients and interacts with the database. Provides the following functions: </p>
<li>1. User authorization.</li> 
<li>2. Getting a list of equipment.</li> 
<li>3. Adding new hardware.</li> 
<li>4. Getting a list of entries for specific equipment.</li> 
<li>5. Recording the user for a certain time interval on the equipment, if it is free.</li> 
<li>6. The client application that will connect to the server and interact with it.</li> 
<p></p>
  <p>The client application provides the following functions:</p>
<li>a) User authorization.</li>
<li>b) Getting a list of equipment.</li>
<li>c) Adding new equipment.</li>
<li>d) Getting a list of entries for specific equipment.</li>
<li>e) Recording the user for a certain time interval on the equipment, if it is free.</li>

<h2>Database schema</h2>

![photo1681070373](https://github.com/NerdyVal/client-server/assets/114080091/1310550b-770f-4db5-ae19-997f7d79ed71)
