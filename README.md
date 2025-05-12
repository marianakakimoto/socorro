# 🚀 Segurança da Informação - Projeto

## 👤 Integrantes

- Laura Jane Antunes  
- Mariana A. K. Hirata

## 📖 Descrição

Este projeto explora conceitos e práticas essenciais de **segurança da informação**, com o objetivo de implementar soluções eficazes para proteger dados e sistemas.

## 🗂️ Estrutura do Projeto

- **`/app`**: Diretório principal para rotas no novo sistema de roteamento do Next.js (App Router). Contém páginas e layouts.
- **`/components`**: Onde ficam os componentes reutilizáveis da interface.
- **`/hooks`**: Hook personalizado para exibir notificações do tipo toast (mensagens rápidas que aparecem no canto da tela).
- **`/lib`**: Autenticação, implementação da lógica da cifra de César, conexão com o banco de dados e utilidades genéricas.

💡 **Dica**: Mantenha seus sistemas seguros e atualizados! 🔒

---

## 🛠️ Tecnologias Utilizadas

- [Next.js](https://nextjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [React Hooks](https://reactjs.org/docs/hooks-intro.html)
- [ESLint](https://eslint.org/)
- [Toast Notifications (como Sonner ou Radix UI)](https://sonner.emilkowal.dev/)

---

## 🚧 Como rodar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repo.git
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Rode o projeto:
   ```bash
   npm run dev
   ```

4. Acesse:
   ```
   http://localhost:3000
   ```

---

## 🎯 Funcionalidades

- 🔐 Criptografia de mensagens com cifra de César
- 🔑 Sistema de autenticação de usuários
- 📢 Exibição de mensagens de alerta/toast
- 🧩 Layout responsivo com navegação intuitiva

---

## 🔒 Conceitos de Segurança da Informação

- **Confidencialidade**: uso da cifra de César para proteger dados sensíveis  
- **Autenticação e controle de acesso**: módulo `auth.ts`  
- **Boas práticas de desenvolvimento seguro**  
- **Gerenciamento de sessões e dados**

---

## 🚀 Melhorias Futuras

- Implementar autenticação via JWT
- Substituir a cifra de César por criptografia moderna (ex: AES)
- Adicionar logs e monitoramento de segurança
- Integração com banco de dados remoto
- Implementar controle de permissões por perfil de usuário

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT**.  
Sinta-se livre para usar, modificar e compartilhar com atribuição.
