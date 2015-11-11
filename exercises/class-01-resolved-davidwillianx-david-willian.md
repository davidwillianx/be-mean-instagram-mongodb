#MongoDB - Aula1 - Exercicio 

##Importando dados (Restaurantes)

```
davidwillianx@davidwillianx:~/Development/node/bemean/mongodb$ mongoimport --db bemean --collection restaurantes --drop --file restaurantes.json 
2015-11-09T23:33:26.150-0300	connected to: localhost
2015-11-09T23:33:26.150-0300	dropping: bemean.restaurantes
2015-11-09T23:33:26.837-0300	imported 25359 documents
```

##Contando os restaurantes
> db.restaurantes.find({}).count();
25359
> 
