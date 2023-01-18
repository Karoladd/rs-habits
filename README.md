Foco. Prática. Grupo.
node - tecnologia que permite a execução JavaScript no lado do backend
node -v
npm init -y
npm i fastify
TypeScript - tipagem de dados trazendo inteligência para o editor de código(VSCode) para ele identificar possíveis erros antes do código ir para a produção.
npm i typescript -D
npx tsc --init
tsconfig.json - "target":"es2020"
npm i tsx -D
npm i tsx src/server
package.json 
  "scripts": {
      "dev": "tsx --watch src/server.ts"
    },
npm run dev
Fastify é mais permormático do que o express.
Método HTTP: Get(busca informação), Post(cria), Put(atualiza recurso completo), Patch (atualiza recurso específico), Delete (deleta um recurso dentro do backend)
npm i -D prisma
npm i @prisma/client
npx prisma init --datasource-provider SQLite
Extensão VSCode: prisma
npx prisma migrate dev

REACT NATIVE
npx expo install expo-font @expo-google-fonts/inter

RUN PROJECTS
npm i
server/ .env