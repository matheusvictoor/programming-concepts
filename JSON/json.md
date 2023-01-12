# JSON (JavaScript Object Notation) 

JSON é um formato de dados leve e fácil de ler e escrever, que é utilizado para transmitir informações em aplicações web. Ele é baseado em texto simples e é facilmente convertido para e de objetos JavaScript, tornando-o uma escolha popular para intercâmbio de dados entre aplicativos web e servidores.

Um arquivo JSON consiste de pares de chave-valor, como um objeto JavaScript, e pode conter dados de vários tipos, como números, strings, booleanos, listas e objetos aninhados. Cada par chave-valor é separado por vírgulas e os objetos aninhados são delimitados por chaves.

```json
{
    "nome": "João",
    "idade": 30,
    "endereco": {
        "rua": "Rua dos Bobos",
        "numero": 0,
        "bairro": "Centro",
        "cidade": "São Paulo",
        "estado": "SP"
    },
    "hobbies": ["corrida", "leitura", "viagem"]
}
```

É possível trabalhar com esses dados em javascript utilizando as funções JSON.parse() e JSON.stringify() para transformar esses dados em objetos javascript e vice-versa.

JSON é amplamente utilizado em APIs REST (Representational State Transfer) para enviar e receber dados em formatos textuais, já que é fácil de se ler e escrever, fácil de se processar e possui uma estrutura leve, facilitando a sua comunicação entre diferentes sistemas, plataformas e linguagens de programação