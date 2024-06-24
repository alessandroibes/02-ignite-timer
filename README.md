# ignite-timer

## Descrição

Este projeto foi desenvolvido durante o módulo 02 do curso de ReacjJS da Rocketseat, módulo que aprofunda os conceitos em Hooks passando enquanto aborda outros assuntos como ContextAPI, useReducer, immer, dentro outros.

### Styled Components

Este projeto utiliza **Styled Components** (https://styled-components.com/) para criar a estilização da aplicação. O Styled Components é uma biblioteca de CSS-in-JS que permite que a gente utilize o CSS dentro do JavaScript e em um formato parecido com os do React, adicionando muitas funcionalidades à estilização da aplicação.

### ESList

O **ESLint** é usado neste projeto, pois o mesmo permite que a gente configure diversas regas para padronizar a organização do nosso código. Isso vai desde como deve ser o comportamento de quebras de linha, ponto-e-vírgula, vírgulas e até mesmo regras para nomeação de variáveis ou
plugins que ajudam (https://www.npmjs.com/package/eslint-plugin-react-hooks) a gente à não esquecer algumas regras do React.

Caso queira ver as configurações utilizadas nesse plugin, você pode acessar o repositório oficial com o código dessas configurações para o React: https://github.com/Rocketseat/eslint-config-rocketseat/blob/main/react.js

O ESLint possui uma enorme lista de rules (regras) que você pode configurar, e todas estão disponíveis através desse link da documentação oficial: https://eslint.org/docs/rules/

Caso queira ver mais sobre como configurar o ESLint manualmente, você pode ver o guia de Getting Started do ESLint disponível no seguinte link: https://eslint.org/docs/user-guide/getting-started

### Router

A biblioteca **react-router-dom** (https://reactrouter.com) é utilizada para prover o roteamento da aplicação.

### Forms

A biblioteca **react-hook-form** (https://react-hook-form.com/) é utilizada para recuperar os dados dos inputs dos formulários. Esta biblioteca permite trabalhar-mos com os formulários tanto de uma maneira **Controlled** quanto **Uncontrolled**.

A biblioteca **zod** (https://github.com/colinhacks/zod) é utilizada em conjunto com o react-hook-form para adicionar mais camadas de validação aos formulários. A biblioteca zod foi utilizada por trazer um pouco mais de integração com o TypeScript (IntelliSense).

Para a integração do react-hook-form com bibliotecas de validação, foi necessário usar a biblioteca **@hookform/resolvers**.

OBS: a validação é utilizada apenas para entendimento do funcionamento das validações usando a biblioteca react-hook-form, visto que a mesma não é realmente necessário neste projeto, pois as validações necessárias já são realizadas pelo próprio HTML.

## Bibliotecas utilizadas

- [styled-components] (https://www.npmjs.com/package)

```shell
npm i styled-components
```

- [react-router-dom] (https://www.npmjs.com/package/react-router-dom)

```shell
npm i react-router-dom
```

- [phosphor-react] (https://www.npmjs.com/package/phosphor-react)

```shell
npm i phosphor-react
```

- [react-hook-form] (https://www.npmjs.com/package/react-hook-form)

```shell
npm i react-hook-form
```

- [zod] (https://www.npmjs.com/package/zod)
- [@hookform/resolvers] (https://www.npmjs.com/package/@hookform/resolvers)

```shell
npm i zod
npm i @hookform/resolvers
```

### Bibliotecas usadas apenas para desenvolvimento

- [@types/styled-components] (https://www.npmjs.com/package)

```shell
npm i @types/styled-components - D
```

- [eslint] (https://www.npmjs.com/package/eslint)

```shell
npm i eslint -D
```

- [@rocketseat/eslint-config] (https://www.npmjs.com/package/@rocketseat/eslint-config)

```shell
npm i @rocketseat/eslint-config -D
```

## Para executar a aplicação

Baixar dependências:

```shell
npm i
```

Executar o comando:

```shell
npm run dev
```

## Telas da aplicação
