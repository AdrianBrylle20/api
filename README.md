# API Name





 


## API
Description:


 


## API
Endpoints
 


## Request
API Payload





 


## Response

API Response:

The response for most endpoints contains a JSON object with a status field (either "success" or "error") and a data field. The structure of the data field varies based on the specific endpoint.

For /postName:
{
    "status": "success",
    "data": null
}

For /getName:
{
    "status": "success",
    "data": [
        {"lname": "Hortizuela", "fname": "Manny"},
        {"lname": "Licayan", "fname": "Arnold"}
    ]
}


For /updateName:
{
         "status":"success","data":null
}

For /deleteName:
{
         "status":"success","data":null
}.


 


## Usage


To retrieve a greeting with a concatenated full name, make a GET request to /getName/{lname}/{fname}.

To add a new name, make a POST request to /postName with a JSON payload containing fname and lname.

To retrieve a list of names, make a GET request to /getName.

To update an existing name, make a POST request to /updateName with a JSON payload containing id, fname, and lname.

To delete a name, make a POST request to /deleteName with a JSON payload containing id.


 


## License
No license




 


## Contributors


Prof. Manny Hortizuela & Mary Joy Paras


 


## Contact
Contact Information:
Gmail: parasmj17@gmail.com
