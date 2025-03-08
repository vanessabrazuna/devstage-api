![Cover](./.github/cover.png)

# Devstage Api

Um sistema de indicações que conecta desenvolvedores a comunidades e oportunidades em tecnologia.

## Requisitos

- Node.js;
- TypeScript;
- Tsup;
- Fastify;
 - Fastify Cors;
 - Fastify Swagger;
 - Fastify Swagger UI;
 - Fastify Type Provider Zod;
- Zod;
- Docker;
- Biome;

## Configuração

- Clonar o repositório;
- Instalar dependências (`npm install`);
- Configurar PostgreSQL e Redis (`docker compose up -d`);
- Copiar `.env.example` arquivo (`cp .env.example .env`);
- Rodar aplicação (`npm run dev`);
- Teste! (Eu pessoalmente recomendo testar com [Hoppscotch](https://hoppscotch.io/)).

## HTTP

### POST `/subscriptions`

Crie uma nova rota

#### Request body

```json
{
  "name": "string",
  "email": "user@example.com",
}
```

#### Response body

```json
{
  "name": "string",
  "email": "string",
}
```

### GET `/example/:exampleId`

Retorna dados de uma única pesquisa.


#### Response body

```json
{
	"": "",
	"": "",
}
```

### POST `/example/:exampled/example`

Adicione algo

#### Request body

```json
{
  "": "",
}
```

## WebSockets

### ws `/example/:exampleId/example`

#### Message

```json
{
  "": "",
	"": "",
}
```
---

## 👩‍💻 Desenvolvedora

Feito com 💜 por **[Vanessa Brazuna](https://github.com/vanessabrazuna)**

Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/vanessabrazuna) para acompanhar mais projetos incríveis! 🚀

---
