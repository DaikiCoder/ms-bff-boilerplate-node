# ms-bff-boilerplate-node

Microservice BFF Boilerplate with Node.js, Express and Typescript.

## Steps

npm init\
npm i express\
npm i -D typescript @types/express @types/node\
npx tsc --init

**tsconfig.json**

- "target": "ES2022"
- "module": "NodeNext"
- "moduleResolution": "NodeNext"
- "outDir": "dist"
- "noImplicitAny": true
- "include": ["src"]

Create env files for local and prod\
npm i -D concurrently\
Add scripts to run proyect\

npm init @eslint/config\
npm i -D prettier eslint-config-prettier\
Format Document With, Format on save\
