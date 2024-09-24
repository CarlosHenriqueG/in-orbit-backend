<div align="center">
  <h1>in.orbit</h1>
</div>

## Sobre a aplicação
### A in.orbit é um aplicação que ajuda você a definir e cumprir suas metas pessoais. Com ele, você pode:

- Criar suas metas: Adicione objetivos que deseja alcançar.
- Registrar conquistas: Quando completar uma meta, o app registra a data e a hora.
- Visualizar progresso: Consulte suas metas organizadas por dia da semana.

## Rotas da aplicação

- POST /goals: Cria uma nova meta.
- POST /completions: Completa um meta usando o id da meta.
- GET /summary: Lista todas as metas.
- Get /pending-goals: Lista todoas metas pendentes.


## Tecnologias 💻

- [NODE](https://vitejs.dev/)
- [DRIZZLE](https://react.dev/)
- [TYPESCRIPT](https://www.typescriptlang.org/)
- [POSTGRES](https://www.postgresql.org/) (NeonDB) ou (Supabase)
- [FASTIFY](https://tailwindcss.com/)
- [BIOMEJS](https://biomejs.dev/)

## Configuração do Servidor
Para configurar o backend do in.orbit, siga os passos abaixo:

### Requisitos:
- Node.js 
- postgres (ou outro banco de dados que preferir)
- Também pode rodar pelo [docker](https://www.docker.com/) (é só usar o docker compose dentro do projeto)

### Para rodar este projeto, além de clonar este projeto, é preciso estar com o front-end funcionando.
#### para acessar o repositório do front-end, clique aqui: [in.orbit backend](https://github.com/CarlosHenriqueG/in-orbit-frontend.git?tab=readme-ov-file#readme) 

### Clone o projeto
```bash
  git clone https://github.com/CarlosHenriqueG/in-orbit-backend.git
```
### Entre no diretório do projeto
```bash
  cd in-orbit-backend
```
### Instale as dependências
```bash
  pnpm install
```
### configure o banco de dados
- Crie um banco de dados Postgres atualize as configurações no arquivo .env.

### Inicie o servidor
```bash
  pnpm run dev
```
- Obs: você pode mudar o pnpm pelo npm se desejar.

# Contribuição
Sinta-se à vontade para contribuir! Abra uma issue ou envie um pull request.

# Licença
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)