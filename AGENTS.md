# AGENTS.md — DevLinks

## 1. Identidade do projeto

**Nome:** DevLinks  
**Tipo:** Projeto acadêmico — Projeto 03  
**Objetivo:** Desenvolver uma aplicação web para centralizar links de um perfil em uma interface simples, organizada e responsiva.

A aplicação deve seguir o protótipo disponibilizado no Figma, respeitando sua identidade visual, organização dos elementos, espaçamentos e comportamento nos diferentes tamanhos de tela.

## 2. Tecnologias obrigatórias

Utilizar exclusivamente as seguintes tecnologias como base do projeto:

- React 19
- TypeScript
- Vite 8
- Tailwind CSS 4
- React Hooks
- Context API
- localStorage

Ferramentas de apoio:

- OpenCode para assistência durante o desenvolvimento.
- Context7 para consultas à documentação oficial.
- Playwright para testes e validações no navegador.

Não adicionar bibliotecas ou dependências sem necessidade justificada e sem aprovação do responsável pelo projeto.

## 3. Referência visual

Figma oficial:

https://www.figma.com/design/j3LzPTa8KDp4VhuAHpsvjA/DevLinks-%E2%80%A2-OpenCode-MiniProject--Copy-?node-id=0-1

O protótipo apresenta quatro variações:

- Desktop Light.
- Desktop Dark.
- Mobile Light.
- Mobile Dark.

Elementos principais:

- Avatar centralizado.
- Identificação do perfil.
- Controle de alternância de tema.
- Quatro botões de links.
- Ícones de redes sociais.
- Rodapé com identificação/autoria.

### Regras de fidelidade visual

- Priorizar a fidelidade ao Figma.
- Respeitar cores, tipografia, dimensões, bordas, espaçamentos e alinhamentos.
- Garantir a adaptação entre desktop e dispositivos móveis.
- Não adicionar elementos visuais que não estejam previstos no protótipo sem autorização.
- Não substituir a identidade visual por estilos genéricos.

## 4. Arquitetura e organização

Organizar o código de forma modular, separando responsabilidades.

Estrutura planejada:

```text
src/
├── assets/
├── components/
│   ├── features/
│   └── ui/
├── context/
├── data/
├── hooks/
├── App.tsx
├── index.css
└── main.tsx

AGENTS.md
README.md
```

Responsabilidades:

- `components/ui`: componentes visuais reutilizáveis.
- `components/features`: componentes relacionados às funcionalidades da aplicação.
- `context`: Context API e gerenciamento global de estado.
- `data`: informações dos links e dados estáticos.
- `hooks`: Hooks personalizados.
- `assets`: imagens, ícones e recursos visuais.
- `App.tsx`: composição principal da aplicação.
- `index.css`: estilos globais e configurações visuais.

Não concentrar toda a aplicação em um único componente.

## 5. Padrões de desenvolvimento

- Utilizar componentes funcionais React.
- Utilizar TypeScript com tipagem adequada.
- Utilizar Props para comunicação entre componentes.
- Aplicar React Hooks para gerenciamento de estado e efeitos.
- Utilizar Context API quando houver necessidade de compartilhar estados entre componentes.
- Manter responsabilidades bem definidas.
- Utilizar nomes claros e consistentes.
- Evitar duplicação de código.
- Preferir componentes reutilizáveis.
- Manter o código organizado e legível.

## 6. Tema claro e escuro

A aplicação deverá possuir dois temas:

- Light Mode.
- Dark Mode.

Requisitos:

- Permitir a alternância entre os temas.
- Utilizar Context API para compartilhar o tema quando apropriado.
- Persistir a preferência do usuário no `localStorage`.
- Recuperar a preferência ao carregar a aplicação.
- Garantir que todos os elementos visuais respeitem o tema selecionado.
- Evitar inconsistências durante a inicialização da aplicação.

## 7. Responsividade

A aplicação deverá funcionar corretamente em:

- Desktop.
- Tablets.
- Smartphones.

Regras:

- Seguir as versões desktop e mobile do Figma.
- Evitar rolagem horizontal.
- Garantir que os botões e ícones sejam acessíveis.
- Manter espaçamentos e alinhamentos adequados.
- Utilizar os recursos responsivos do Tailwind CSS.

## 8. Links e interações

- Todos os links devem direcionar aos destinos corretos.
- Utilizar URLs válidas.
- Links externos devem abrir de maneira apropriada.
- Os ícones de redes sociais devem ser clicáveis.
- Os elementos interativos devem apresentar comportamento consistente.
- Evitar links fictícios ou sem destino.

## 9. Tratamento de erros e validações

- Evitar erros no console do navegador.
- Corrigir problemas de renderização.
- Validar o funcionamento das interações.
- Verificar a persistência do tema.
- Validar os links.
- Verificar o comportamento em diferentes resoluções.
- Executar o build e o lint antes de considerar uma entrega concluída.

## 10. Testes e documentação

Utilizar Playwright para validar:

- Carregamento da aplicação.
- Funcionamento dos links.
- Alternância entre temas.
- Persistência do tema após atualização.
- Responsividade em desktop e mobile.

Utilizar Context7 para consultar documentação atualizada das tecnologias, especialmente React, Vite e Tailwind CSS.

Registrar evidências reais da utilização dessas ferramentas, sem simular resultados.

## 11. Escopo do projeto

### Dentro do escopo

- Página de perfil com avatar.
- Identificação do usuário.
- Botões de links.
- Ícones de redes sociais.
- Alternância Light/Dark.
- Persistência de tema.
- Responsividade.
- Testes com Playwright.

### Fora do escopo

- Sistema de autenticação.
- Cadastro de usuários.
- Banco de dados.
- Painel administrativo.
- Backend ou API própria.
- Gerenciamento dinâmico de links por usuários.

Não implementar funcionalidades fora do escopo sem autorização.

## 12. Orientações para agentes de IA

Antes de realizar alterações:

1. Analisar a estrutura existente.
2. Consultar este arquivo e o README.
3. Verificar se a implementação respeita o Figma.
4. Explicar alterações relevantes antes de executá-las.
5. Evitar sobrescrever arquivos sem necessidade.

Durante o desenvolvimento:

- Trabalhar em etapas pequenas.
- Não modificar tecnologias obrigatórias sem autorização.
- Não inventar funcionalidades.
- Não remover recursos já implementados sem justificativa.
- Priorizar soluções simples, legíveis e compatíveis com o projeto.
- Explicar decisões técnicas importantes para que o responsável pelo projeto compreenda o código.

Após alterações:

- Verificar erros de TypeScript.
- Executar o lint.
- Executar o build quando aplicável.
- Informar quais arquivos foram alterados e o que foi implementado.

**Regra principal:** a implementação deve atender aos requisitos acadêmicos e manter fidelidade ao protótipo do Figma.