# seal()

- Read(allowed).

- updation(allowed).

- write & delete (not allowed).

# freeze()

# defineProperty()

# defineProperties()

# seal()

# assign()

    assign function is used to concat the JSON object.

# spread operator()

    immutability

    ES6

    ...obj

# entries()

- to convert JSON object to JSON array

Used to covert object to array

# fromEntries()

- convert array to object

# delete()

- to delete key & value pairs.

  delete obj.p_cost;

# flat()

- single dimensional array use flat()

## important function in JSON

1. freeze()

2. seal()

3. entries()

4. fromEntries()

5. defineProperty()

6. defineProperties()

7. assign()

8. delete

Website: https://restcountries.eu/
rest/v2/all

How to iterate loop ? forEach

Fields in the API.

                name
                capital
                population
                region
                nativeName
                flag
                numericCode

## object to string conversion

    JSON.stringify()

## string to object

    JSON.parse()

# JSON Server

    JSON server helps to create the REST API 's based on JSON data.

    Ex.
        GET
        POST
        PUT
        DELETE
        HEAD
        TRACE
        OPTIONS
        ----
        ---

    JSON Server is light weight server.

    JSON Server by default running on port no.3000

    we will install JSON Server by using following command.

> npm install -g json-server

    ==> npm stands for node packaging  manager

    ==> -g stands for global installation.

open cmd prompt --> npm install -g json-server --> installation complete.

we will load the JSON data in JSON Server by using following command.

> json-server --watch demo.json

Why JSON Server?
