## Data section
We need to collect data from all gyms in the city of Seville, including their name, identification, location (address, latitude, longitude) and then search for the "hot" neighbor where most of the place is located. For the purpose of data assets, we use FourSquare and apply folio to visualize a particular neighbor in which we will observe customer "traffic" and predict the proper location of the new gym in the city.

For that purpose we will use the Request "GET https://api.foursquare.com/v2/venues/explore" with the "query": "Gym".
We will be working with data like this:

	           uid	                       name	        shortname	   postalcode	     lat	   lng
	4b6021f5f964a520cfd629e3	Club Metropolitan	Gym / Fitness	     41018	  37.383451	-5.975261



Finally the searched location will appear on the folio map with the name "Lugar Buscado".
