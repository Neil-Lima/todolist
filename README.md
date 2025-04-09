# ✅ Lista de Tarefas - ToDo List Full Stack

<div align="center">
  <img src="frontend/public/logo192.png" alt="ToDo List Logo" width="200" />
</div>

## 📋 Sobre o Projeto

Desenvolvi esta aplicação de lista de tarefas (ToDo List) como uma solução completa para organização e gestão de atividades do dia a dia. O projeto utiliza tecnologias modernas tanto no frontend quanto no backend, oferecendo uma experiência de usuário fluida e responsiva.

### ✨ Recursos Principais

- **Gerenciamento Completo de Tarefas**: Adicionar, editar, excluir e marcar tarefas como concluídas
- **Categorização**: Organizar tarefas por categorias personalizáveis
- **Priorização**: Definir níveis de prioridade para as tarefas
- **Filtros Avançados**: Filtrar tarefas por status, data ou categoria
- **Datas de Vencimento**: Definir e acompanhar prazos
- **Modo Escuro/Claro**: Interface adaptável à preferência do usuário
- **Layout Responsivo**: Funciona perfeitamente em dispositivos móveis e desktop

## 🚀 Tecnologias Utilizadas

### Frontend
<div style="display: inline-block">
  <img align="center" alt="React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="TypeScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" alt="SASS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sass/sass-original.svg">
  <img align="center" alt="React Query" height="30" width="40" src="https://raw.githubusercontent.com/TanStack/query/main/media/emblem-light.svg">
  <img align="center" alt="Axios" height="30" width="40" src="https://axios-http.com/assets/logo.svg">
</div>

- React.js para construção da interface
- TypeScript para tipagem estática
- React Query para gerenciamento de estado e cache
- Axios para requisições HTTP
- SASS para estilização avançada
- React Icons para ícones personalizados
- Jest e Testing Library para testes

### Backend
<div style="display: inline-block">
  <img align="center" alt="NestJS" height="30" width="40" src="https://nestjs.com/img/logo-small.svg">
  <img align="center" alt="TypeScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
  <img align="center" alt="MongoDB" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg">
  <img align="center" alt="Node.js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
</div>

- NestJS como framework backend
- TypeScript para desenvolvimento tipado
- MongoDB como banco de dados NoSQL
- Mongoose para modelagem de dados
- Jest para testes unitários e E2E
- Class-validator para validação de dados

### DevOps
<div style="display: inline-block">
  <img align="center" alt="Docker" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg">
  <img align="center" alt="NGINX" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg">
  <img align="center" alt="GitHub Actions" height="30" width="40" src="https://github.githubassets.com/images/modules/site/features/actions-icon-actions.svg">
</div>

- Docker para contêinerização
- Docker Compose para orquestração de contêineres
- NGINX como servidor web e proxy reverso
- GitHub Actions para CI/CD

## 🔧 Instalação e Configuração

### Usando Docker (Recomendado)
```bash
# Clone o repositório
git clone https://github.com/Neil-Lima/todolist.git
cd todolist

# Inicie os contêineres com Docker Compose
docker-compose up -d
```

A aplicação estará disponível em:
- Frontend: http://localhost:80
- Backend API: http://localhost:3333

### Instalação Manual

#### Backend
```bash
# Na pasta do projeto
cd backend

# Instale as dependências
npm install

# Configure as variáveis de ambiente (crie um arquivo .env)
# MONGODB_URI=mongodb://localhost:27017/todolist_db

# Inicie o servidor em modo de desenvolvimento
npm run start:dev
```

#### Frontend
```bash
# Na pasta do projeto
cd frontend

# Instale as dependências
npm install

# Inicie o aplicativo React
npm start
```

## 📱 Funcionalidades

- **Gestão de Tarefas**:
  - Criar, editar, visualizar e excluir tarefas
  - Marcar tarefas como completas
  - Atribuir prioridades (Alta, Média, Baixa)
  - Definir datas de vencimento

- **Organização**:
  - Categorizar tarefas
  - Aplicar filtros múltiplos
  - Ordenar por diferentes critérios

- **Experiência do Usuário**:
  - Interface intuitiva e amigável
  - Notificações para tarefas próximas do vencimento
  - Persistência de dados via API

## 🏗️ Arquitetura

O projeto segue uma arquitetura moderna de aplicação web:

- **Frontend**: SPA (Single Page Application) em React com TypeScript
- **Backend**: API RESTful construída com NestJS
- **Banco de Dados**: MongoDB com Mongoose para modelagem
- **Infraestrutura**: Containerização com Docker e Docker Compose
- **Servidor Web**: NGINX para servir o frontend e como proxy reverso para o backend

## 📞 Contato

- **Email**: victorneil08@gmail.com
- **LinkedIn**: [Neil Lima](https://www.linkedin.com/in/neil-lima-706606248)
- **GitHub**: [Neil-Lima](https://github.com/Neil-Lima)

---

⌨️ Desenvolvido com ❤️ por Victor Lima