# Proiect Programare Avansata 2021 :tada:

Autori:  Maria Gabriela Coteanu 

### Cerința:

#### Correct an address :earth_americas:
- Write an algorithm that corrects the fields country, state, city of a postal
  address. 
  ##### Example: Country: RO, State: New York, City: Iasi -> will become -> Country: RO, State: Iasi, City: Iasi
- the algorithm needs to have unit tests and integration tests for performance
  and precision
- ideally the algorithm will work for all countries in the world and a few
  languages
- Expose a REST api using spring boot that will receive a postal address and
  return the corrected result
- Deploy the application as a docker container in aws/heroku or other using a
  continuous deployment pipeline



#### :heavy_check_mark: Pentru a rula aplicația local, trebuie rulat serverul, deschis portul dat în browser (ex: localhost:8081 ).

##### :heavy_check_mark: De asemenea, aplicația este încărcată în cloud, la adresa: https://correct-the-address.herokuapp.com/.

##### :heavy_check_mark: Link-ul către documentația generată cu swagger: http://localhost:8081/swagger-ui.html

##### :heavy_check_mark: În fișierul "app.log" din directorul "logs" sunt păstrate rezultatele tuturor rulărilor.

### Screenshot

![img.png](img.png)

![img_2.png](img_2.png)

![img_1.png](img_1.png)


### :collision: OBS: 
At laboratory I worked in pair with Narcis Stefan Barat where he made the deployment, but for this repository, I made it myself.