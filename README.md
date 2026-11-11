# DevLinks — Projeto 03

## 1. Sobre o projeto

O **DevLinks** é uma aplicação web desenvolvida com React e TypeScript, cujo objetivo é reunir e disponibilizar links importantes de um perfil em uma única página, com uma interface simples, organizada e responsiva.

O desenvolvimento tem como referência o layout disponibilizado no Figma, contemplando os modos claro (*Light Mode*) e escuro (*Dark Mode*), além de versões para desktop e dispositivos móveis.

## 2. Tecnologias utilizadas

- **React 19:** construção da interface por meio de componentes.
- **TypeScript:** tipagem estática e maior segurança no desenvolvimento.
- **Vite 8:** ambiente de desenvolvimento e ferramenta de build.
- **Tailwind CSS 4:** estilização e implementação do layout responsivo.
- **React Hooks:** gerenciamento de estado e efeitos da aplicação.
- **Context API:** compartilhamento de informações entre componentes.
- **localStorage:** persistência da preferência de tema do usuário.
- **Playwright:** testes e validação da aplicação no navegador.
- **Context7:** consulta à documentação oficial das tecnologias utilizadas.
- **OpenCode:** apoio ao desenvolvimento com inteligência artificial.

## 3. Funcionalidades previstas

- Exibição de perfil com avatar e identificação.
- Apresentação de links externos.
- Acesso às redes sociais por meio de ícones.
- Alternância entre os temas claro e escuro.
- Persistência da preferência de tema após atualizar a página.
- Layout adaptável para desktop e dispositivos móveis.

## 4. Organização do projeto

A estrutura será organizada para separar componentes, dados, hooks e arquivos de configuração, facilitando a manutenção e a evolução da aplicação.

```text
src/
├── assets/
├── components/
│   ├── features/
│   └── ui/
├── data/
├── hooks/
├── App.tsx
└── index.css

AGENTS.md
README.md
```

## 5. Como executar o projeto

### Pré-requisitos

- Node.js instalado.
- npm instalado.

### Instalação

```bash
npm install
```

### Executar em desenvolvimento

```bash
npm run dev
```

### Gerar versão de produção

```bash
npm run build
```

### Executar validação de código

```bash
npm run lint
```

### Visualizar a versão de produção

```bash
npm run preview
```

## 6. Testes e validações

O projeto contará com testes utilizando Playwright para verificar o funcionamento dos links, a alternância de temas e a responsividade da interface.

Também serão utilizadas consultas ao Context7 para apoiar a implementação com base na documentação das tecnologias.

## 7. Referência visual

O desenvolvimento seguirá o protótipo disponibilizado no Figma:

[DevLinks — OpenCode MiniProject](https://www.figma.com/design/j3LzPTa8KDp4VhuAHpsvjA/DevLinks-%E2%80%A2-OpenCode-MiniProject--Copy-?node-id=0-1)

## 8. Status

Projeto acadêmico em desenvolvimento — Projeto 03.
