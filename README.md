# UFOs

## Background 
  - The UFO sightings webpage will be updated to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria dynamically.  This ability to search and refine the list is real time will make for a better user experience and aid people interacting with the web page in more effectively and efficiently searcing though the UFO sightins. The data filter is workiing correctly and now we will be adding filterss for the city, state, country, and shape.

## Results: 
   - This added search criteria are shown here.  The user needs to enter the search criteria into the fileds provided, press the enter key and the table with UFO sightins will be updated.  IF further filtering is desired additional criteria can be entered in the remaining fields, the program will read that input and refie the list according to all criteria entered by the user.

### Examples

Searching is accomplished using the entry fileds on the left side of the page

![UFO Search Instructions](https://user-images.githubusercontent.com/91839403/152858215-bc512959-0684-477e-be99-a4f7124a7118.jpg)

#### 1.  Unfiltered starting page

![Unfiltered UFO data screenshot](https://user-images.githubusercontent.com/91839403/152860954-32a1e192-d576-4909-8d1c-418a492aba1b.jpg)

#### 2. Filtered on data 1/12/2010

![Data filtered 01122010 UFO data screenshot](https://user-images.githubusercontent.com/91839403/152860762-23164288-b53b-4283-8fe3-807317c80e07.jpg)

#### 3. Filtered on 1/12/2010 and State "or"

![Data filtered 01122010 and state or UFO data screenshot](https://user-images.githubusercontent.com/91839403/152861291-a45fea0b-1ce1-4ed7-9bac-09a10b1dee65.jpg)

4. Filtered on 1/12/2010 and State "or" and finally on shape "changing"

![Data filtered 01122010 and state or and shape changing UFO data screenshot](https://user-images.githubusercontent.com/91839403/152861611-e3a96ffd-42d9-4e46-b9be-5842764d77a2.jpg)

#### 5. This example shows date can be left alone and we can search on variables like state and shape. In this case State - "ca" and shape "light"

![Data filtered 01122010 state ca and shape light](https://user-images.githubusercontent.com/91839403/152861958-54ca7876-7d43-4c50-ab01-f86c60417f5e.jpg)

#### 6. The code to achieve this is the following:

![image](https://user-images.githubusercontent.com/91839403/152856738-ac4a3da2-4488-4edb-831e-6f68a44ea317.png)


## Summary

Overall with the current page we are now able to filter the data on several criteria individually or at the same time.  The filtering capability works well.
There are still improvements possible.  The data here is only from one year, clearly a more comprehensive global data set would provide more insight and make the site itself more useful.  This, while true wont be the focus of the potential improvements.  The scope of these recommendations and shortcomings will be focused on the user experience of the web page. 

#### Shortcomings:
There are 2 shortcomings that come to mind in my evaluation.
1) There is no button that will allow us to clear the search parameters in total and/or indivdually. The entries must be cleared manually.
2) The entry must match the list but no drop down selection bases on the actual data still available to select is provided. This requires the user to enter it and know what the options are.

These shortcomings lead easily to some proposed and next step page enhancements.
1) Provide a drop down selection from the actual data with a "none" options.  That would simplify entry, validate the data and enhance the suer experience.
2) Add a "clear all" button to clear all current selections and allow a new search criteria.






