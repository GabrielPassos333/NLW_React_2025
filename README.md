# NLW Connect - REACT

Este projeto foi desenvolvido durante o evento **NLW Connect** da [Rocketseat](https://rocketseat.com.br/), uma semana intensiva de aprendizado e desenvolvimento de aplicações modernas.

O projeto consiste em uma aplicação web para fazer um sistema de indicações de amigos para um evento, com um sistema de ranking e estatísticas. Com isso teremos um ranking de indicações e um sistema de pontuação para os usuários.

## Tecnologias Utilizadas

- [Next.js 14](https://nextjs.org/) - Framework React com renderização híbrida e server components
- [React](https://react.dev/) - Biblioteca para construção de interfaces
- [TypeScript](https://www.typescriptlang.org/) - Superset JavaScript com tipagem estática
- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS utility-first
- [Zod](https://zod.dev/) - Validação de schemas TypeScript
- [ORVAL](https://orval.dev/) - Gerador de clientes API TypeScript a partir de OpenAPI
- [Lucide React](https://lucide.dev/) - Ícones para a interface

## Estrutura do Projeto

```
├── app/
│   ├── (home)/             # Página inicial e formulário de inscrição
│   └── invite/             # Páginas de convite, estatísticas e ranking
│       └── [subscriberId]  # Página de convite individual
├── components/             # Componentes React reutilizáveis
├── http/                   # Funções de chamada à API (gerado pelo Orval)
├── public/                 # Arquivos estáticos
└── ...
```

## Getting Started

Siga estas instruções para executar o projeto localmente:

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/nlw-connect-projeto.git
cd nlw-connect-projeto
```

2. Instale as dependências:

```bash
npm install
```

3. Execute o desenvolvimento:

```bash
npm run dev
```

Abra [http://localhost:3000](http://localhost:3000) no seu navegador para ver o resultado.

## Sobre o NLW Connect

O NLW Connect é um evento promovido pela Rocketseat focado em conectar desenvolvedores com as tecnologias mais modernas do mercado. Durante o evento, desenvolvemos este projeto completo utilizando o stack mais atual de desenvolvimento web.

## Aprendizado

Para saber mais sobre as tecnologias utilizadas:
#falar sobre o que aprendeu

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/docs)

Desenvolvido com 💜 durante o NLW Connect da Rocketseat
