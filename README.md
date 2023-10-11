# perfetto-documentation
Swagger Documentation for GitHub Pages

How to generate Swagger-UI pages using Official Docker Image
1. Pull official image from hub
`docker pull swaggerapi/swagger-ui`
2. Run docker image
`docker run -p 80:8080 -e SWAGGER_JSON=/app/swagger.yaml -v $(pwd):/app swaggerapi/swagger-ui`
3. After run copu data from `/usr/share/nginx/html`
4. Change href in files 
