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
📦 Como Rodar o Projeto Localmente
Para rodar o projeto em seu ambiente local, siga as instruções abaixo:

Pré-requisitos
Antes de começar, certifique-se de ter o Node.js (versão 14 ou superior) e o npm (ou yarn) instalados em seu sistema. Caso não tenha, instale o Node.js através do site oficial.

Passo 1: Clone o Repositório
Clone o repositório para sua máquina local:

bash
Copiar código
git clone https://github.com/usuario/ecosrev.git
cd ecosrev
Passo 2: Instalar as Dependências
Navegue até o diretório do projeto e instale as dependências tanto do frontend quanto do backend:

Frontend
Entre na pasta do frontend e instale as dependências:

bash
Copiar código
cd frontend
npm install
Backend
Entre na pasta do backend e instale as dependências:

bash
Copiar código
cd backend
npm install
Passo 3: Configurar as Variáveis de Ambiente
O projeto exige algumas variáveis de ambiente para funcionar corretamente. Crie um arquivo .env no diretório raiz do projeto (se ainda não existir) e configure as seguintes variáveis:

env
Copiar código
MONGO_URI=seu_mongo_uri
JWT_SECRET=sua_chave_secreta
PORT=porta_backend
CLIENT_URL=URL_do_frontend
MONGO_URI: A URL de conexão com o banco de dados MongoDB.
JWT_SECRET: Uma chave secreta para gerar tokens JWT.
PORT: A porta onde o backend estará rodando (exemplo: 5000).
CLIENT_URL: URL onde o frontend estará rodando (exemplo: http://localhost:3000).
Passo 4: Rodar o Projeto
Agora, você pode rodar o frontend e o backend em seu ambiente local:

Frontend
Execute o servidor de desenvolvimento do frontend:

bash
Copiar código
cd frontend
npm run dev
O frontend estará disponível em http://localhost:3000.

Backend
Execute o servidor de desenvolvimento do backend:

bash
Copiar código
cd backend
npm run dev
O backend estará disponível em http://localhost:5000 (ou qualquer porta configurada no .env).

📄 Documentação da API
A API do projeto está documentada e pode ser acessada pelo Swagger. Após rodar o backend, você pode acessar a documentação da API no seguinte endereço:

bash
Copiar código
http://localhost:5000/api-docs
A documentação fornece detalhes sobre as rotas disponíveis, parâmetros necessários, exemplos de requisições e respostas, além de explicar o fluxo da autenticação via OAuth 2.0.

🧑‍🤝‍🧑 Contribuindo
Contribuições são sempre bem-vindas! Para contribuir com o projeto, siga as etapas abaixo:

Faça um fork do repositório.
Clone o repositório para sua máquina local.
Crie uma branch para sua feature ou correção.
Implemente suas alterações e escreva testes quando necessário.
Envie um pull request com uma descrição detalhada sobre o que foi alterado.
Se possível, adicione testes automatizados para garantir a qualidade do código.

📜 Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais informações.

📝 Contato
Se você tiver dúvidas ou sugestões, entre em contato pelo email:
contato@ecosrev.com

Ou acesse o repositório no GitHub:
https://github.com/usuario/ecosrev

🎨 Design e Interfaces
A plataforma foi projetada com uma interface limpa e intuitiva, priorizando a experiência do usuário. O design segue a filosofia de Atomic Design, garantindo que os componentes sejam reutilizáveis e facilmente escaláveis. A paleta de cores foi escolhida para ser suave e amigável, com destaque para tons de roxo e azul, transmitindo modernidade e confiança.

🧑‍💻 Desenvolvedores
Este projeto foi desenvolvido por uma equipe de estudantes do curso de Laboratório de Desenvolvimento Web. Abaixo estão os nomes dos principais colaboradores:

Fulano de Tal - Frontend Developer
Ciclano da Silva - Backend Developer
Beltrano Oliveira - UX/UI Designer
Agradecemos à comunidade open-source, cujas bibliotecas e ferramentas ajudaram a tornar este projeto possível.

