---
id: send-message-text
title: Enviar texto simples
---

## Método

#### /send-text

`GET` https://api.z-api.io/instances/SUA_INSTANCIA/token/SEU_TOKEN/send-text

---

## Conceituação

Como proprio nome do método já diz "enviar texto", utilizamos ele para enviar mensagens, é um metodo bem simples mas você pode incremetar e deixar ele mais "charmozinho" utilizando formataçao e emojis, se você ainda não sabe como formatar textos clique nos links abaixo e siga as instruções:

- Como [formatar fontes] no Whatsapp

- Onde [copiar emojis]

[formatar fontes]: https://faq.whatsapp.com/general/chats/how-to-format-your-messages/?lang=pt_br
[copiar emojis]: https://getemoji.com/

:::tip Sobre emojis

O que você precisa saber é que ele é um caracter ASCII normal assim com existe a fonte Times New Roman por exemplo, existem fontes de emojis, pense que você pode criar sua própria galeria de emojis.

Para fazer o teste basta copiar um emoji e colar em seu texto, você pode usar este aqui 🤪 se quizer :)

:::

---

## Atributos

| Atributos | Tipo | Descrição |
| :-- | :-: | :-- |
| phone | string | Telefone do destinatario no formato DDI DDD NUMERO Ex: 551199999999. **IMPORTANTE** Envie somente números sem formataçao ou máscara |
| message | string | Texto a ser enviado |

---

## Code
