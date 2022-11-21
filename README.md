# Python REST APIs With Flask, Connexion, and SQLAlchemy

**Disclaimer** : Both the tutorial and the code can be found [here](https://realpython.com/flask-connexion-rest-api) by [RealPython](https://github.com/realpython). I am just a learner not the code owner nor the author.

# Setup
1. Create a virtual environment for the project
2. Install Flask framework (version 2.2.2)
3. Install Connexion swagger to perform http requests (version 2.14.1)
4. Initiate the flask server
5. Configure the API specifications
6. Add the relevant operation identifiers

# Notes about the work
1. The api design obeys OpenAPI specs.
1. Visiting 127.0.0.1:8000/api/people will output the list of all people
2. Visiting 127.0.0.1:8000/api/ui will displays the Swagger UI for API commands

# I learned in part one:
---
* Build a base Flask project with a REST API
* Handle HTTP requests with Connexion
* Define API endpoints using the OpenAPI specification
* Interact with your API to manage data
* Build API documentation with Swagger UI

---
**End notes and further references**
1. [More about the requirements and the virtual environment](https://realpython.com/python-virtual-environments-a-primer/).
2. [Templating using Jinja Template Engine](https://realpython.com/primer-on-jinja-templating/)