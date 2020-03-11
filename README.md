# Maana Measurement
The maana-measurement service is a Maana Q workspace service for unambiguously 
representing different kinds of measurements.   It includes definitions of over
50 commonly used kinds of measurements drawn from multiple engineering and
science disciplines:

* Classical Mechanics
* Fluid Mechanics
* Heat Transfer
* Mass Transfer 
* Thermodynamics
* Waves and Optics
* Digital Information

It also includes definitions of over 100 of the some of the most commonly used 
units of measure found in scientific literature.  

## Installation
The Maana Measurement service can be installed using the Maana Export and Import
assistant.    To import this service, create a new workspace and name it 
"Maana Measurement".   

![Add workspace](https://github.com/maana-io/maana-measurement/blob/master/img/MakeNewService.png)

After the workspace has loaded, add the "Maana Export Import Assistant" to the
workspace's inventory.   One way of adding the assistant is to search for it 
using the Maana Rank global search feature, and dragging the assistant from the
search results onto the inventory panel. 

![ready to import](https://github.com/maana-io/maana-measurement/blob/master/img/ready-to-import.png)

Once the assistant has been added, select the workspace object in the inventory
and then open the assistant.   Drag the maana-measurement.q-export.json file 
from this folder onto the assistant.   It may take a while to import all the 
service's kinds and instances.   When it is complete, you will see a message 
like the one below:

![import completed](https://github.com/maana-io/maana-measurement/blob/master/img/import-results.png)

Finally, set the workspace's public and template properties to true so that other 
users can access the service.   Don't forget to press save!

![save workspace](https://github.com/maana-io/maana-measurement/blob/master/img/Save-workspace.png)

## Using the Service
