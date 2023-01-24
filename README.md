# Encurtador de URL


## Endpoints

•	Cadastrar URL  -  POST  localhost:8080/encurtadores </br>
    Obs: Caso a URL já esteja cadastrada, você receberá como retorno a URL encurtada que já foi feita
    
```
 {
     "url" : "https://github.com/williamledo/ApiTDS"
 }
```

• Estatísticas -   GET localhost:8080/encurtadores</br>
    Para ter acesso as estatisticas das URL's criadas
```
 [
    {
        "urlEncurtada": "localhost:8080/3e86d",
        "qtdDeAcessos": 1,
        "urlOriginal": "https://github.com/williamledo/ApiTDS"
    }
]
```

