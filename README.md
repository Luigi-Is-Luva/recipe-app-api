Recipe API
A RESTful API for recipe management built with Django REST Framework, Docker, and deployed on AWS EC2. Supports user authentication, recipe/ingredient/tag CRUD, image uploads, and API documentation with Swagger.

Features
-User registration, login, and JWT authentication
-CRUD operations for recipes, ingredients, and tags
-Recipe image upload support
-Fully documented API with Swagger UI
-Containerized with Docker
-Deployed on AWS EC2

Technologies{Django, Django REST Framework, Python, Docker, AWS EC2, Swagger, PostgreSQL, Pytest}

Getting Started
Prerequisites
-Docker and Docker Compose installed
-Access to AWS EC2 instance (optional for deployment)

Running Locally
1.-Clone the repository
2.-SSH into AWS EC2:
    ssh ec2-user@3.137.145.56  
3.-Start the Docker containers:
    docker-compose -f docker-compose-deploy.yml up -d  
4.-The API should be available at:
http://ec2-3-137-145-56.us-east-2.compute.amazonaws.com/api/docs/ (Swagger UI)
5.-Admin panel:
http://ec2-3-137-145-56.us-east-2.compute.amazonaws.com/admin/

API Documentation
Access the Swagger UI for interactive API docs and testing at:
http://ec2-3-137-145-56.us-east-2.compute.amazonaws.com/api/docs/

Running Tests
Run unit tests with:
  pytest  
  
Deployment
The app is containerized using Docker and deployed on AWS EC2. Docker Compose is used to orchestrate services.

Contact
For questions or demo requests, please contact pokeluigi43@gmail.com

Contact
For questions or demo requests, please contact [your-email@example.com]
