
# API GATEWAY
a basic api gateway written in python and using  [flask](https://github.com/pallets/flask "flask")  to forward your requests to the designated endpoint
- Supports only GET and POST methodes
- It can be easily dockerized

#### Instructions

1. - Configure the routing.xlsx file
2. - (optional) change the listening url in the code default : http://ip_adress/api/v1/service_name;
1. - Run 

  ```python
  pip install -r  requirements.txt
```
3. - Run your python code;


#### File organisation

    python/
            routing.xlsx
            requirements.txt
	    	main.py
	     	docker-compose.yaml
	     	DockerFile
           


