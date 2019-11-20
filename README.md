# PyJamas Conf 2019

https://pyjamas.live - Python ao vivo do seu sofá, no seu canal 🛋 💻 🐍

Queremos transmitir o maior número de conteúdo #python em português (pt-BR)
em 24 horas.

O intuito é atingir brasileiros espalhados por todo o mundo, nos mais variados fusos 🌎 🕐

Você pode colaborar fazendo uma transmissão online no seu canal de YouTube ou Twitch.

## Quando?

**Inicio**: 13 de Dezembro de 2019, Sexta-Feira 16h (BRT)
**Final**: 14 de Dezembro de 2019, Sábado 16h (BRT)

*(Horário de Brasília)

## Perguntas Frequentes

- Quais são as regras?
  > Você deve concordar em seguir o [CDC](https://github.com/pyjamasconf/codigo-de-conduta)
  > Sua transmissão deve tratar sobre #Python ou algum tema relacionado (tecnologias integraveis com Python, Comunidade, Carreira etc)

- Qual horário devo apresentar minha transmissão?
  > Você pode escolher qualquer horário entre `13/12/2019 16:30 (BRT)` e `14/12/2019 15:30 (BRT)`
  > Podem ocorrer multiplas transmissões no mesmo horário

- Como farei a transmissão?
  > Fazer a transmissão é de responsabilidade de quem está propondo a atividade

  > Você pode usar o seu próprio canal do [Youtube](https://www.youtube.com) ou [Twitch](https://www.twitch.tv)

  > Você pode organizar com outros palestrantes para compartilhar um mesmo canal

  > Ao submeter a proposta deverá incluir o link para a transmissão (pré agendada no youtube preferencialmente) ou para o canal onde ela ocorrerá

- Qual ferramenta devo utilizar para fazer a transmissão?

  > A ferramenta para transmitir pode ser qualquer uma que você já conheça, o mais recomendado é o [OBS](https://obsproject.com/download). Nele é possível transmitir câmera, tela, áudio etc..

  > [Como usar OBS para fazer transmissão ao vivo](https://vidmonsters.com/blog/como-usar-obs/)

- Qual plataforma de vídeo devo utilizar?

  > Preferencialmente [Youtube](https://www.youtube.com) ou [Twitch](https://www.twitch.tv), pois essas plataformas mantém a gravação e não têm limite de expectadores.

- Estou enfrentando problemas com a transmissão. O quê devo fazer?
  > Entre em contato com a nossa organização e iremos lhe ajudar.
  
  > Email: pyjamasconf@gmail.com

  > Twitter: https://twitter.com/pyjamasconf

# Envie sua proposta


> **DICA**: Se preferir edite o `talks.json` e envie o PR diretamente na UI do github https://github.com/pyjamasconf/pyjamas-conf-2019/blob/master/talks.json (clique no ícone 🖍 e edite o arquivo em seu fork, e então envie o PR atraves do navegador mesmo)

OU...

## 1 - Faça um fork deste reposítório

https://github.com/pyjamasconf/pyjamas-conf-2019/fork

## 2 - Faça o clone do repositório localmente

```bash
git clone git@github.com:{SEU_USERNAME_AQUI}/pyjamas-conf-2019.git
cd pyjamas-conf-2019
git checkout -b minha_talk
```

## 3 - Edite o arquivo `talks.json` adicionando sua proposta

**Atenção**: As chaves do JSON são sem acento e em letras minúsculas.

**Todos os dados são obrigatórios**

- titulo - str - Título da sua proposta - 140 chars
- palestrantes - list[dict] - Lista de palestrantes
- publico - str - Opções: "iniciante", "intermediário", "avançado"
- descricao - str - Descrição da sua palestra - 280 chars
- tags - list[str] - Lista de tags referentes a sua proposta [veja sugestão de tags](#tags)
- formato - str - Opções: "slides", "conversa", "live-code", "debate"
- duracao - int - Duração em minutos, ex: 60
- inicio - str - Formato: YYYY-MM-DD HH:MM periodo válido entre: 2019-12-13 16:30 e 2019-12-14 16:00 (horario de Brasilia)
- url - str - Url para a seu link de stream ex: http://Youtube.com/c/SeuCanal ou http://Youtube,com/watch?id=78878sfsdf

**talks.json**
```js
{
  "talks": [
    // Adicione sua proposta no final do json,
    {
      "titulo": "Título da minha talk",
      "palestrantes": [
          {"nome": "Fulana", "link": "http://twitter.com/fulana", "img": "http://path/to/avatar.jpg|png"},
          {"nome": "Sicrano", "link": "http://sicrano.me", "img": "http://path/to/avatar.jpg|png"}
       ],
       "publico": "iniciante",
       "descricao": "Nessa talk vamos falar sobre X, Y e Z",
       "tags": ["xis", "ipsilum", "zê", "live-code"],
       "formato": "slides",
       "duracao": 60,
       "inicio": "2019-12-13 17:30",
       "url": "http://Youtube.com/watch?cvnwhvjvhf"
    },
  ]
}
```

## 4 Faça o commit e push das suas alterações

```bash
git add talks.json
git commit -am "Proposta: Titulo da minha talk"
git push -u origin HEAD
```

## 5 Envie um Pull Request

https://github.com/pyjamasconf/pyjamas-conf-2019/compare/master...SEU_USERNAME_AQUI:minha_talk

## 6 Aguarde o seu PR ser aprovado

Iremos fazer o review da sua proposta aguarde comentários e updates no seu PR.


---


# Tags

- Web
- Django
- Flask
- DRF
- Data Science
- Just Python
- Automação
- Comunidade
- API
- Test
- QA
- Scrap
- Empreendedorismo com python
- Python Basico
- Bot
- DevOps
- CI/Deploy
