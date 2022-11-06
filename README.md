# UFO Analysis

## Overview
  The purpose of this analysis is to help Dana create a website with a dynamic table full of UFO sightings in the US and Canada. The table will be filtered each time a user interacts with it.

## Resources
  - Javascipt
  - Visual Studio Code 1.73
  - HTML
  
## Results
  
  ### Making a search
  The following image is the filter box along with the unfiltered dataset the user will see and interact with when they visit our site. We included placeholders to demonstrate an example input to guide the user.
 
![image](https://user-images.githubusercontent.com/110706169/200195485-58019af6-8a5d-416d-bc2b-661047a7dfc1.png)

First we filter by country, the table will not change much since most of our data is from the US.
![image](https://user-images.githubusercontent.com/110706169/200195813-e75f32b8-51b0-48a8-ada7-4d84809fd7d9.png)

We can narrow our search by adding another filter such as **City** or **State**. In the following example we use California as an example(must be abbreviated).
![image](https://user-images.githubusercontent.com/110706169/200196007-f6b266c8-ab52-44b6-99de-06f1e73fd6e0.png)
From the image we can see the table has filtered the data by **State**.

We can continue narrowing our data adding more filters. We enter "EL CAJON" in our **City** filter.
![image](https://user-images.githubusercontent.com/110706169/200196146-718d40af-a099-4a1c-8f13-bf887b8dd062.png)

We have narrowed our search down to 5 entries all located in El Cajon, California, US. At this point we don't need to narrow our search any further.

## Summary
One drawback of this website is that the dataset is very limited and new data points must be added manually to the dataset to keep our website updated.

- Recommendations: 
 1. Currently to filter by State or Country you **must** use abbreviation. This isn't great design, what if the user doesn't know a certain abbreviation and even if they do, its a massive Quality of Life change for the site if the user can enter the full names.
  
 2. Initially, to successfully filter any data, the user input had to match exactly to our dataset.
  
    ![image](https://user-images.githubusercontent.com/110706169/200196794-ab9355b3-0699-40a1-b848-46e16e1ea3ed.png)
    
    If the user was to enter "Benton" in the **City** filter nothing would show up. We fixed this by making sure the user input was being changed to lower case to match out data.
    
    ![image](https://user-images.githubusercontent.com/110706169/200196958-204fa7b4-b94d-4ed2-b941-1a0bc97657ae.png)
    
  Now, even if the user was to enter something like this:
  
![image](https://user-images.githubusercontent.com/110706169/200197194-93df00d1-d75b-462a-bf3f-274e5be033ef.png)

  We can still find what we are looking for.
  
