#API CEP-BEMEAN

## A Idéia:
Em conversa com [Higor Diego](https://github.com/higordiego) e [Michel Souza](https://github.com/souzacristsf), resolvemos criar uma api de CEP para os alunos e as demais pessoas que amam projetos open source. Então em menos de 2 dias o projeto já estava rebendo mais de 50 requisições/dias e crescendo. 

## Documentação CEP Bemean
Conforme esse projeto for evoluindo, documentaremos com alguns exemplos de utilização da api para que assim vocês tirem um bom proveito da api. Para usar é bem simples, basta seguir os exemplos abaixo, em caso de duvida ou sugestões, entrar em [contato](https://telegram.me/bemean) ou abra uma *issue* aqui no repositorio que analisaremos.

## Webservice de CEP
Envie um CEP nos seguintes formatos com **{8}** ou **{9}** digitos. 
Utilize os seguintes exemplos.

> [https://cep-bemean.herokuapp.com/api/br/88370410](https://cep-bemean.herokuapp.com/api/br/88370410) 
> [https://cep-bemean.herokuapp.com/api/br/88370-410](https://cep-bemean.herokuapp.com/api/br/88370-410)

Retorno em **Json**:
```javascript
{
    "code": "88370-410",
    "state": "SC",
    "district": "Centro",
    "address": "Rua Ezequiel Antero Rocha",
    "city": "Navegantes"
}
```

## Tecnologias Utilizadas
![](/img/express.png) ![](/img/mongodb.png) ![](/img/nodejs.png)

## Hosting Cloud
![](/img/heroku.jpg)

## CEP não encontrado ou retornamos um desatualizado?
Contribua com esse projeto. Envie sua sugestão que analisaremos. 
**"Sua necessidade hoje, pode ser a nossa amanhã."**

### Creditos:
 + [Higor Diego](https://github.com/higordiego) 
 + [Michel Souza](https://github.com/souzacristsf)