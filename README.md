# ChatOps

O ChatOps é uma poderosa metodologia que integra comunicação instantânea e automação para melhorar a colaboração, a produtividade e a eficiência das equipes de desenvolvimento, operações e suporte. Ao combinar ferramentas de chat e automação, o ChatOps centraliza as informações e ações em uma única plataforma, permitindo que as equipes trabalhem de maneira mais colaborativa e responsiva.

## Getting Started

Site:https://chatopsconsole.vercel.app/

bot:https://t.me/groupOps_bot


## Documentação da API

#### Retorna todos os itens

```http
  GET https://api.telegram.org/bot${apiKey}/unbanChatMember?chat_id=${groupName}&username=${username}
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |


