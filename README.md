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
 
## Components
This service consists of two components:

* `Maana Measurement`: A Maana Q Workspace service which provides a type safe mechanism for representing over 50 different classes of measurement (physical dimensions).
* `Maana Measurement Utilities`: (optional) A Maana Q workspace service that provides utilities for converting between PhysicalQuantities and Measurement kinds.

# Installing the Measurement Service
As a pre-requisite, the Maana Q platform must be deployed and the `Lambda Assistant` and `Import Export Assistant` must be installed.   If these pre-requisites have been satisfied, you can install the `Maana Measurement` by logging into the `Maana Intelligence Designer` and follow the instructions below:

1. Create a new workspace and name it 
"Maana-Measurement". Give it the workspace id "maana-measurement".   

![Add workspace](https://github.com/maana-io/maana-measurement/blob/master/img/MakeNewService.png)

2. After the workspace has loaded, add the `Maana Export Import Assistant` to the workspace's inventory.   Search for it using the search bar.   Hit the `+` sign next the the search result to add it to your inventory. 

![ready to import](https://github.com/maana-io/maana-measurement/blob/master/img/ready-to-import.png)

3. Once the `Export Import Assistant` has been added, select the workspace object in the inventory and then select the `Export Import Assistant` in the dropdown of the assistant pannel.   
4. Drag the `maana-measurement.q-export.json` file from the root folder in this repo onto the assistant.   It may take a while to import all the service's kinds and instances.   When it is complete, you will see a message like the one below:

![import completed](https://github.com/maana-io/maana-measurement/blob/master/img/import-results.png)

5. Finally, set the workspace's `public` property to `true` so that other users can access the service.   *Don't forget to press save!*

![save workspace](https://github.com/maana-io/maana-measurement/blob/master/img/Save-workspace.png)

# Installing the Utility Service
As a pre-requisite, the Maana Q platform must be deployed and the `Lambda Assistant` and `Import Export Assistants` must be installed.   Also, the 
following additional services must be installed:

* [Maana Physical Quantity](https://github.com/maana-io/maana-physical-quantity-logic)
* [maana-physical-quantity-logic](https://github.com/maana-io/maana-physical-quantity-logic)
* `Maana Measurement`
  
If these pre-requisites have been satisfied, you can install the `Maana Measurement Utilities` by logging into the `Maana Intelligence Designer` and follow the instructions below:

1. Create a new workspace and name it 
"Maana Measurement Utilities". Give it the workspace id "maana-measurement-utilities".   

![Add workspace](https://github.com/maana-io/maana-measurement/blob/master/img/MakeNewUtilitiesService.png)

2. After the workspace has loaded, add the `Maana Export Import Assistant` to the workspace's inventory.   Search for it using the search bar.   Hit the `+` sign next the the search result to add it to your inventory. 

![ready to import](https://github.com/maana-io/maana-measurement/blob/master/img/ready-to-import-utilities.png)

3. Once the `Export Import Assistant` has been added, select the workspace object in the inventory and then select the `Export Import Assistant` in the dropdown of the assistant pannel.   
4. Drag the `maana-measurement-utilities.q-export.json` file from the root folder in this repo onto the assistant.   It may take a while to import all the service's kinds and instances.   When it is complete, you will see a message like the one below:

![import completed](https://github.com/maana-io/maana-measurement/blob/master/img/import-results.png)

5. Finally, set the both the workspace's `public` properties to `true` so that other users can access the service.   *Don't forget to press save!*

![save workspace](https://github.com/maana-io/maana-measurement/blob/master/img/Save-Utilities-workspace.png)

