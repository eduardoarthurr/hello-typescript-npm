Aqui está o **README.md** já formatado de forma limpa, organizada e profissional:

---

# 🟦 Projeto: Primeiros Passos com TypeScript

Este repositório foi criado com o objetivo de aprender os fundamentos do **TypeScript**, incluindo:

* Tipagem básica
* Estrutura de um projeto TypeScript
* Como usar o **NPM**
* Configuração inicial do **tsconfig.json**
* Primeiro “Hello World” em TypeScript

É um projeto simples, focado no entendimento da base antes de avançar para conceitos mais complexos.

---

## 🚀 Tecnologias Utilizadas

* **TypeScript**
* **Node.js**
* **NPM**

---

## 📦 Como iniciar o projeto

### 1️⃣ Inicializar o NPM

```bash
npm init -y
```

### 2️⃣ Instalar o TypeScript como dependência de desenvolvimento

```bash
npm install typescript --save-dev
```

### 3️⃣ Criar o arquivo de configuração do TS

```bash
npx tsc --init
```

### 4️⃣ Ajustar o `tsconfig.json` (opcional, mas recomendado)

Exemplo de configurações básicas:

```json
{
  "compilerOptions": {
    "module": "nodenext",
    "target": "esnext",
    "rootDir": "./src",
    "outDir": "./dist"
  }
}
```

---

## ▶️ Compilar e executar

### Compilar o TypeScript:

```bash
npx tsc
```

### Rodar o JavaScript gerado:

```bash
node dist/index.js
```

---

## 📚 Comandos úteis do NPM

| Comando                   | Descrição                                        |
| ------------------------- | ------------------------------------------------ |
| `npm init -y`             | Cria o arquivo *package.json* com valores padrão |
| `npm install <pacote>`    | Instala um pacote como dependência               |
| `npm install <pacote> -D` | Instala como dependência de desenvolvimento      |
| `npx tsc`                 | Compila o TypeScript usando o tsconfig           |
| `npm run <script>`        | Executa comandos definidos no *package.json*     |

---

## 📁 Estrutura do Projeto

```
📦 projeto-typescript
 ┣ 📂 src
 ┃ ┣ 📄 app.d.ts  
 ┃ ┣ 📄 app.d.ts.map   
 ┃ ┣ 📄 app.js  
 ┃ ┣ 📄 app.js.map 
 ┃ ┗ 📄 app.ts
 ┣ 📄 package-lock.json 
 ┣ 📄 package.json
 ┣ 📄 tsconfig.json
 ┗ 📄 README.md
```

---

## 🎯 Objetivo do Projeto

O foco deste repositório é aprender a base do desenvolvimento com **TypeScript**, incluindo:

* Criar um projeto TS do zero
* Entender tipagem
* Ver como o NPM organiza dependências
* Compilar código TypeScript → JavaScript

Ideal para quem está começando no ambiente **Node + TypeScript**.
