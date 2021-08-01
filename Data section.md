## Data section
We need to collect data from all gyms in the city of Seville, including their name, identification, location (address, latitude, longitude) and then search for the "hot" neighbor where most of the place is located. For the purpose of data assets, we use FourSquare and apply folio to visualize a particular neighbor in which we will observe customer "traffic" and predict the proper location of the new gym in the city.

For that purpose we will use the Request "GET https://api.foursquare.com/v2/venues/explore" with the "query": "Gym".
Finally the searched location will appear on the folio map with the name "Lugar Buscado".