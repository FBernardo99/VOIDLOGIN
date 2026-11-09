# Void Learning

Portal acadêmico demonstrativo desenvolvido com React, TypeScript e Vite.

## Executar localmente

1. Instale Node.js (versão compatível com as dependências do projeto).
2. Abra o terminal nesta pasta, onde está o `package.json`.
3. Execute `npm install`.
4. Execute `npm run dev` e abra o endereço exibido pelo Vite.

A rota inicial abre a tela de login (`/login`). Preencha usuário/e-mail e senha com qualquer valor para entrar no painel demonstrativo.

> A autenticação é ilustrativa e funciona apenas no front-end. Para autenticação real, conecte um backend ou provedor de identidade.

## Recursos desta versão

- Tela de login moderna com imagem de campus, formulário central e detalhes verdes.
- Alternância de visibilidade da senha e validação de campos obrigatórios.
- Dashboard com banner SVG animado preservado e botão “Ver Disciplinas” com hover, foco por teclado e navegação.
- Ajustes de largura para melhor aproveitamento de telas desktop.
- Melhor contraste dos rótulos de itens pendentes no tema escuro.

## Produção

Execute `npm run build` para gerar a pasta `dist`.
