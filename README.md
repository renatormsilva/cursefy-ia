# AI Course Generator :rocket:

## Overview :mag:

Uma plataforma movida por IA para criação e gerenciamento de cursos online. Construída com Next.js e integrada com Clerk para autenticação, Gemini API para conteúdo gerado por IA e Firebase para armazenamento de arquivos, esta plataforma permite que os usuários criem, acompanhem e gerenciem seus cursos, enquanto administradores podem supervisionar o gerenciamento de usuários e cursos.

## Installation :wrench:

- **Clone o repositório**

  ```bash
   git clone https://github.com/mrpankajpandey/ai-course-generator.git
  ```

- **Navegue até o diretório do projeto**

  ```bash
   cd ai-course-generator
  ```

- **Instale as dependencias**

  ```bash
   npm install
  ```

- **Crie um`.env.local`/**

  ```javascript
   NEXT_PUBLIC_CLERK_FRONTEND_API=<your-clerk-frontend-api>
   CLERK_API_KEY=<your-clerk-api-key>
   GEMINI_API_KEY=<your-gemini-api-key>
   FIREBASE_API_KEY=<your-firebase-api-key>
   FIREBASE_PROJECT_ID=<your-firebase-project-id>
   DATABASE_URL=<your-database-url>
  ```

- **Run the development server**

  ```bash
   npm run dev
  ```
