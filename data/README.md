README for First steps in spatial data handling and visualization tutorial


# SUMMARY
The data for this tutorial consists of three datasets:  

- **stl_neighborhoods**: A shape file which consists of the neighborhoods of St. Louis
- **stl_restaurants**: A csv file that consists of restaurants that are in St. Louis within the zip codes 63101, 
63102, and 63103.
- **stl_poi**: A csv file that consists of selected sightseeing spots in St. Louis.


# DATA DESCRIPTIONS
1. **stl_neighborhoods**: This shape file was obtained from the City of St. Louis data portal. St. Louis consists of 79 neighborhoods. This shape file includes these fields:  
  - NHD_NUM: Number of the neighborhood.
  - ANGLE: No information available.
  - NHD_NUMTXT: Neighborhood with neighborhood number.
  - SHAPE_area: Area of the shape file.
  - SHAPE_len: Length of the shape file.
  - geometry:latitude and longitude of the neighborhood.
  - For more information about a specific neighborhood, refer to to the City of St. Louis neighborhood information webpage: https://www.stlouis-mo.gov/live-work/community/neighborhoods/index.cfm. 

2. **stl_restaurants**: This csv is a listing of 115 restaurants which were compiled from a combination of a Google search along with an article from the Riverfront Times on St. Louis restaurants (https://www.riverfronttimes.com/foodblog/2020/03/17/st-louis-restaurants-now-offering-delivery-curbside-and-carryout.). This csv file includes these fields:  
  - Restaurant: Restaurant name.
  - Address: Address of the restaurant.
  - City: City of where the restaurant is located.
  - State: State of where the restaurant is located.
  - ZIP_Code: Zip code of where the restaurant is located.
  - Phone_Number: Phone number of the restaurant.
  - Type: Type of restaurant. Some of the restaurants types might need further explanation. Here is additional information on such types of restaurants:
  	- Asian fusion: Cuisine that combines cuisines of different Asian countries using non-traditional ingredients. Source: https://en.wikipedia.org/wiki/Fusion_cuisine.
  	- Bistro: A small restaurant that serves reasonably priced meals. Source: https://en.wikipedia.org/wiki/Bistro.
  	- Calzone: An Italian oven-baked turnover made with pizza filling and pizza dough. Source: https://en.wikipedia.org/wiki/Calzone.
  	- Dinner theater: Dinner theaters combine a restaurant meal along with a play or musical. Source: https://en.wikipedia.org/wiki/Dinner_theater.
  	- Soul food: African-American originating from the Southern United States. Source: https://en.wikipedia.org/wiki/Soul_food.
  - Rating: Yelp ratings for each restaurant.
  - Review_No: Number of reviews per restaurant.

3. **stl_poi**: This csv file is a listing of 20 records of areas of interest within the city of St. Louis. Examples of such areas of interest are museums, parks, landmarks, and historical buildings. This csv file includes these fields:  
  - POI: Name of the point of interest.
  - Address: Address of the point of interest.
  - City: City of the point of interest. 
  - State: State of the point of interest.
  - Zip code: Zip code of the point of interest.
  - Type: Point of interest type.
  - Lat: Latitude of the point of interest.
  - Long: Longitude of the point of interest.

# CONTACT INFORMATION
For more information about the dataset, please contact either Sébastien Rochette (sebastien@thinkr.fr), Dorris Scott (doritolay@gmail.com), or Jakub Nowosad (nowosad.jakub@gmail.com) 	








