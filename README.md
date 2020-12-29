# People disappeared in Spain from Goverment public data


In order to make statitstics from data this week, I would like to know what information could be visualize and what information could be nece to find out relations eachother.

For now I'm going to make the study in R 

# First Step Scrapping DATA

From Goverment page I've found a servlet which return json with all information. So the first attempt will be to break down this call and try to extract json data to R

```
  
  https://cndes-web.ses.mir.es/publico/Desaparecidos/dao/ServletDesaparecidos
  
```

From private calls I've found *strict origin when cross origin* and block the call.

