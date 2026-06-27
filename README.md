# certificados-neanmuco

Scaffold inicial para o MVP de certificados digitais com QR Code.

Este repositório foi criado automaticamente por um assistente para fornecer um scaffold mínimo:

- Next.js (app minimal)
- TypeScript
- Prisma (SQLite por padrão)
- Rotas API para autenticação passwordless e criação/verificação de certificados
- Geração de QRCode

Passos para rodar localmente:

1. Instalar dependências:

   npm install

2. Criar arquivo .env com as variáveis necessárias (ver prisma/schema.prisma e .env.example)

3. Rodar migrações:

   npx prisma migrate dev --name init

4. Rodar aplicação:

   npm run dev

Documentação e instruções adicionais serão adicionadas conforme avance o scaffold.
