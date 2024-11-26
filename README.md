# 
<img src="https://github.com/user-attachments/assets/37ec0295-1331-4944-ac2c-fb85503723cd" alt="Banner para Site Sua Nova Sombra Roxo e Azul Moderno Delicado" style="border-radius: 200px; width: 100%; height: auto;">

## 🚀 Visão Geral

**Ecosrev** é uma plataforma web desenvolvida com o objetivo de incentivar o descarte correto de resíduos eletroeletrônicos. A aplicação conecta cidadãos a empresas especializadas em coleta de lixo eletrônico, promovendo a sustentabilidade e a conscientização ambiental. O sistema oferece recompensas para os usuários que participam do descarte responsável de seus resíduos.

Este projeto foi desenvolvido no âmbito do curso de **Laboratório de Desenvolvimento Web**, utilizando tecnologias modernas para garantir uma experiência de usuário de alta qualidade, bem como um backend eficiente e escalável.

---

## 🔧 Tecnologias Utilizadas

### **Frontend**
![Next.js](https://img.shields.io/badge/Next.js-%23000000?style=flat&logo=next.js&logoColor=white)
![React.js](https://img.shields.io/badge/React-%2320232a?style=flat&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-%23007ACC?style=flat&logo=typescript&logoColor=white)
![Atomic Design](https://img.shields.io/badge/Atomic_Design-%2300B4D8?style=flat&logo=html5&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-%23C21325?style=flat&logo=jest&logoColor=white)
![React Testing Library](https://img.shields.io/badge/React_Testing_Library-%23E0E0E0?style=flat&logo=react&logoColor=%23FF6138)
![Storybook](https://img.shields.io/badge/Storybook-%23FF4785?style=flat&logo=storybook&logoColor=white)
![OAuth 2.0](https://img.shields.io/badge/OAuth_2.0-%23A6C8FF?style=flat&logo=oauth&logoColor=white)

### **Backend**
![Express.js](https://img.shields.io/badge/Express.js-%23404d59?style=flat&logo=express&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-%23339933?style=flat&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%2347A248?style=flat&logo=mongodb&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-%2385B8C8?style=flat&logo=swagger&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-%23FF6C37?style=flat&logo=postman&logoColor=white)

### **Deploy**
![Vercel](https://img.shields.io/badge/Vercel-%23000000?style=flat&logo=vercel&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23121011?style=flat&logo=github&logoColor=white)

---

## 💡 Funcionalidades

- **Sistema de recompensas**: Incentiva os usuários a descartarem seus resíduos corretamente em troca de benefícios.
- **Autenticação segura**: Implementação de OAuth 2.0 para garantir a segurança no processo de login e comunicação entre frontend e backend.
- **Documentação e visualização de componentes**: Todos os componentes do frontend estão documentados no **Storybook** para fácil reutilização e entendimento.
- **Testes automatizados**: O código foi testado utilizando **Jest** e **React Testing Library**, garantindo uma cobertura de testes acima de 80%.
- **API bem documentada**: A API do backend é documentada utilizando **Swagger**, oferecendo uma visão clara sobre as rotas e funcionalidades.

---

## 🏗️ Estrutura do Projeto

### **Frontend**
A estrutura do frontend segue o conceito de **Atomic Design**, dividindo a aplicação em componentes menores e reutilizáveis. Abaixo, mostramos um exemplo da organização:

/.idea                # Configurações do ambiente de desenvolvimento (JetBrains)
_mocks                # Mocks utilizados nos testes
projeto               # Configurações gerais do projeto
public                # Arquivos estáticos públicos (imagens, ícones, fontes)
routes                # Configuração das rotas da aplicação
src                   # Código-fonte da aplicação
    ├── /atoms        # Componentes atômicos (simples e reutilizáveis)
    │   ├── Button.js
    │   ├── Input.js
    │   └── FormText.js
    │
    ├── /molecules    # Combinação de átomos em unidades funcionais
    │   ├── LoginForm.js
    │   ├── Card.js
    │   └── InputWithLabel.js
    │
    ├── /organisms    # Agrupamento de moléculas em seções completas da UI
    │   ├── Header.js
    │   ├── Sidebar.js
    │   └── Footer.js
    │
    ├── /templates    # Estruturas de layout usando organismos e moléculas
    │   ├── AuthTemplate.js
    │   ├── MainLayout.js
    │   └── DashboardLayout.js
    │
    ├── /pages        # Páginas completas combinando templates e componentes
    │   ├── LoginPage.js
    │   ├── SignUpPage.js
    │   └── DashboardPage.js
    │
    ├── /themes       # Configurações de temas (cores, tipografia)
    │   ├── theme.js
    │   └── ThemeProvider.js
    │
    └── /assets       # Arquivos de estilo global, como CSS ou SCSS
        ├── styles.css
        └── reset.css
tests                 # Arquivos de teste (unitários e de integração)
    ├── /pages       # Testes das páginas
    │   ├── LoginPage.test.js
    │   ├── SignUpPage.test.js
    │   └── DashboardPage.test.js
    │
    └── /components  # Testes para componentes reutilizáveis
        ├── Button.test.js
        ├── Input.test.js
        └── Card.test.js


