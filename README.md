# Cypress E2E Testing - Projeto de Automação

## 📝 Descrição  
Este projeto contém testes automatizados E2E (End-to-End) utilizando Cypress para validar o fluxo de login do site **Sauce Demo**.

---

## 🚀 Funcionalidades Testadas  
- ✅ Login com sucesso  
- ❌ Login com credenciais inválidas  

---

## 🛠️ Tecnologias Utilizadas  
- **Node.js**  
- **Cypress** 

---

## ⚙️ Pré-requisitos  
- Node.js instalado  
- NPM  

---

## 📥 Instalação  

Clone o repositório:  
```bash
https://github.com/sylviavitoria/cypress-automacao
cd cypress-automacao
```

Instale as dependências:  
```bash
npm install cypress --save-dev
```

---

## 🎮 Executando os Testes  

### Abrir o Cypress Test Runner:
```bash
npx cypress open
```

### Executar testes em modo headless:
```bash
npx cypress run
```

---

## 📁 Estrutura do Projeto  

```
cypress-faculdade/
├── cypress/
│   ├── e2e/
│   │   └── login.cy.js
│   ├── fixtures/
│   │   └── example.json
│   └── support/
│       ├── commands.js
│       └── e2e.js
├── .gitignore
├── cypress.config.js
├── jsconfig.json
└── package.json
```

---

## 🧪 Casos de Teste  

### ✅ Login com Sucesso  
- Acessa a página de login  
- Insere credenciais válidas  
- Verifica redirecionamento para página de inventário  

### ❌ Login com Falha  
- Acessa a página de login  
- Insere credenciais inválidas  
- Verifica mensagem de erro  
- Confirma permanência na página de login
