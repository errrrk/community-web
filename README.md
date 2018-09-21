## Build docker image

```commandline
npm run-script build  
docker build -t community-web .
```

## Run docker image
```commandline
docker run --rm -it -p 8080:8080 community-web 
open http://localhost:8080
open http://localhost:8080/workspace
```
