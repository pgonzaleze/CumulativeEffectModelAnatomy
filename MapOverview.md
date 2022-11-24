* In the central panel it is shown the map of the area of study and the corresponding HUC's. As a default, the "map overview" app shows the data of the Athabasca basin (A) with 103 HUC's (hydrologic unit code). However, the information displayed in this section is automatically adjusted according to the data [uploaded](https://github.com/pgonzaleze/JoeModelAnatomy/blob/main/UploadData.md) by the user (B).
![alt text](https://github.com/pgonzaleze/CumulativeEffectModelAnatomy/blob/main/Figures/MapOverview_comparison.png)

* Below the central panel are buttons to "Adjust Magnitude", run the "Joe Model", or run the "Population model".
![alt text](https://github.com/pgonzaleze/CumulativeEffectModelAnatomy/blob/main/Figures/low_panel_inMapOverview.jpg)
* On the right side are listed the "Stressors variables", each stressor has a dynamic button that if "clicked" will display over the central panel (next to the map) the corresponding system capacity.
    * In addition, if the user, click on the icon with a "graph symbol", a new window pops-up, so that the values can be customized or edited "on the fly". In the example below the value is updated from "0" to "50".
    ![alt text](https://github.com/pgonzaleze/CumulativeEffectModelAnatomy/blob/main/Figures/stressor-response_temp_adult_APP2.jpg)
* Each HUC can be selected so that independent analyses can be performed if desired. For example:
    * Let´s assume the three top-most HUC are selected (will be displayed in turquoise), then the user could be able to adjust the values "on the fly" by clicking on the "Adjust Magnitude" button, but also to perform a "quick" JoeModel.
    * Notice that when the button "Adjust Magbitude" is hit, a window pops-up.
    - [insert figure here]
    * In the pop-up window the user will see a red box with the value (in percent %) after performing a "quick JoeModel" test, with the legend "Mean System Capacity: ".
    * This is also the quickest way to visualize the System Capacity of a set of grouped HUC's.
* Note: The app will disconnect from the server after 20 min of non-use. To prevent missing the current work the user will need to update constantly the app.
![alt text](https://github.com/pgonzaleze/CumulativeEffectModelAnatomy/blob/main/Figures/DisconnectFromServer.jpg)

