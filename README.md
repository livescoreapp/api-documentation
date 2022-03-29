# Live Score API Documentation

This is the official documentation of the Live Score API.

The API is integrated in the Live Score Desktop App (www.live-score-app.com) and available as HTTP REST Api.


## Authorization

You can create a custom Authorization Token within the Desktop App of Live Score.
If you build a custom client using our REST API, please send this token as "Authorization" header within every single request.



## Versioning

Every sport has its own version.
The current version of the Desktop App can be asked with a simple `/version` request.


## Swagger Setup

To allow you an easy playground experience, we've integrated a full Swagger setup for every single sport.
Just start the Swagger Docker container with the prepared `docker-compose.yml` file.

Open the terminal in the same folder as that file, and (if Docker is already installed on your machine)
just run this command.

```ruby 
docker-compose up -d
```

This will download the Docker image and start the container.
Once started, the Swagger API documentation is available at http://localhost



[<img src="https://raw.githubusercontent.com/wiki/livescoreapp/api-documentation/assets/swagger.png">]()






