## Data section
We need to collect data from all gyms in the city of Seville, including their name, identification, location (address, latitude, longitude) and then search for the "hot" neighbor where most of the place is located. For the purpose of data assets, we use FourSquare and apply folio to visualize a particular neighbor in which we will observe customer "traffic" and predict the proper location of the new gym in the city.

For that purpose we will use the Request "GET https://api.foursquare.com/v2/venues/explore" with the "query": "Gym".
We will be working with data like this:

	uid	name	shortname	address	postalcode	lat	lng
0	4b6021f5f964a520cfd629e3	Club Metropolitan	Gym / Fitness		41018	37.383451	-5.975261
1	4e5d3468483b18585970ec10	Gimnasio Sevilla Gym	Gym / Fitness		41002	37.395878	-5.994382
2	4e9ea70c2c5b47f3f525b246	Lowfit	Gym		41020	37.406129	-5.933991
3	4be2f274b02ec9b69a194ec0	Galisport	Gym / Fitness		41013	37.368877	-5.981208
4	4b90c41cf964a520b59633e3	Cuesta Sport	Gym / Fitness		41004	37.389561	-5.991601


Finally the searched location will appear on the folio map with the name "Lugar Buscado".
