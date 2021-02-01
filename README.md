## Cellplot shiny app

This app has been developed to work inside a docker container (Dockerfile file available [here](https://github.com/mpg-age-bioinformatics/shiny)).

To use this app locally you need start the container with:
```bash
docker run --rm -p 3838:3838 --name venndiagram mpgagebioinformatics/shiny-venndiagram
```
Access the app on your browser over [http://localhost:3838/venndiagram](http://localhost:3838/venndiagram).

The container can be stopped and the container removed with:
```bash
docker stop venndiagram && docker rm venndiagram
``` 
Removing the image once you've stopped the container:
```bash
docker rmi venndiagram
```
