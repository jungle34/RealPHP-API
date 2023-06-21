**REST API Example**

***Your API classes should be alocated in /classes in main directory of API***

This is an example REST API that demonstrates how to create a simple endpoint with a POST and a GET request. The API is built using PHP and can be accessed using the URL http://185.28.23.133/api/<endpoint class>/<endpoint module>.
    
**Endpoint Description**

***POST Request***

The POST request is used to add new data to the endpoint. In this example, we will be adding a new user to the system. The request body should be in JSON format and include the following fields:

```json
    {
        "name": "John Doe",
        "email": "johndoe@example.com",
        "phone": "555-555-5555"
    }
    
 ```



***GET Request***

The GET request is used to retrieve data from the endpoint. In this example, we will be retrieving a list of all users in the system. The response body will be in JSON format and will include an array of user objects. Each user object will include the following fields:

```json
    {
        "name": "John Doe",
        "email": "johndoe@example.com",
        "phone": "555-555-5555"
    }
    
 ```

Endpoint Usage

To add a new user to the system, make a POST request to the following URL:

http://host/api/user/add

The request body should be in JSON format and include the user data as described above.

To retrieve a list of all users in the system, make a GET request to the following URL:

http://host/api/user/list

The response body will be in JSON format and will include an array of user objects, as described above.
Conclusion

That's it! You should now have a good understanding of how to create a simple endpoint with a POST and a GET request using PHP. Happy coding!
