# ⚖️ Calculadora de IMC (Índice de Massa Corporal)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)

Uma aplicação web moderna, intuitiva e responsiva desenvolvida para o cálculo rápido e preciso do **Índice de Massa Corporal (IMC)**. Este projeto foi construído para servir como parte do meu portfólio de desenvolvimento Front-End, demonstrando a aplicação de boas práticas em **React**, componentização limpa e build otimizado com **Vite**.

---

## 📌 Sumário

- [Visão Geral](#-visão-geral)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Arquitetura do Projeto](#-arquitetura-do-projeto)
- [Como Executar o Projeto](#-como-executar-o-projeto)
- [Conceitos Aplicados & Aprendizados](#-conceitos-aplicados--aprendizados)
- [Roadmap & Melhorias Futuras](#-roadmap--melhorias-futuras)
- [Licença](#-licença)
- [Contato](#-contato)

---

## 💡 Visão Geral

O Índice de Massa Corporal (IMC) é uma medida internacional usada para calcular se uma pessoa está no peso ideal. Esta ferramenta oferece uma interface simplificada onde o usuário informa peso e altura, recebendo imediatamente a sua classificação e recomendações básicas de saúde.

### 🌟 Destaques do Projeto
- **Feedback em tempo real:** Resposta instantânea assim que os dados são processados.
- **Design Adaptativo:** Funciona perfeitamente em dispositivos móveis, tablets e desktops.
- **Validação de Entrada:** Impede o envio de valores negativos, caracteres inválidos ou campos vazios.

---

## ✨ Funcionalidades

- 📊 **Cálculo Preciso:** Executa a fórmula $IMC = \frac{peso}{altura^2}$ de forma rápida.
- 🏷️ **Classificação Automática:** Identifica e exibe a categoria correspondente:
  - Abaixo do peso
  - Peso normal
  - Sobrepeso
  - Obesidade Grau I
  - Obesidade Grau II
  - Obesidade Grau III (Mórbida)
- 🔄 **Opção de Reset:** Permite limpar os campos rapidamente para uma nova consulta.

---

## 🚀 Tecnologias Utilizadas

- **[React](https://react.dev/):** Biblioteca principal para a criação da interface reativa.
- **[Vite](https://vitejs.dev/):** Ferramenta de build extremamente rápida para o ecossistema Web moderno.
- **JavaScript (ES6+):** Lógica da aplicação, manipulação de estados e funções utilitárias.
- **CSS3:** Estilização modular e design responsivo com Media Queries.
- **ESLint:** Mantenedor da padronização e qualidade do código.

---

## 📁 Arquitetura do Projeto

```text
calculadora_imc/
├── calculadora/
│   ├── src/
│   │   ├── components/      # Componentes reutilizáveis da interface
│   │   ├── utils/           # Funções utilitárias (ex: fórmula e regras do IMC)
│   │   ├── App.jsx          # Componente principal
│   │   ├── main.jsx         # Ponto de entrada da aplicação React
│   │   └── index.css        # Estilos globais e variáveis de tema
│   ├── public/              # Ativos estáticos
│   ├── index.html           # Documento HTML principal
│   ├── package.json         # Dependências e scripts do projeto
│   └── vite.config.js       # Configurações do Vite
└── README.md
