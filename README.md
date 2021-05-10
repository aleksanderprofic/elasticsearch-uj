
To run samples:

1. Run docker compose in docker directory

		$ docker compose up
		or
		$ docker-compose up

2. Import all samples 
	
		$ ./samples/ex_import.sh
		
3. Check if everything is working 

		* Elastic -> http://localhost:9200
		* Kibana -> http://localhost:5601
		* Cerebro -> http://localhost:9000/
		
	in Cerebro connect to `http://elasticsearch:9200`
