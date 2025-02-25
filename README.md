# eFood - Plataforma de Delivery de Comida

Este projeto é uma aplicação de delivery de comida chamada eFood, onde os usuários podem visualizar restaurantes, explorar seus cardápios, fazer pedidos e realizar pagamentos online.

## Sobre o Projeto

O eFood é uma aplicação web desenvolvida em React que permite aos usuários:
- Visualizar uma lista de restaurantes disponíveis
- Ver detalhes e cardápio de cada restaurante
- Adicionar itens ao carrinho de compras
- Realizar o checkout com informações de entrega e pagamento

## Tecnologias Utilizadas

- **React** - Biblioteca JavaScript para construção de interfaces
- **TypeScript** - Superset tipado do JavaScript
- **Redux Toolkit** - Gerenciamento de estado da aplicação
- **React Router** - Navegação entre páginas
- **Styled Components** - Estilização de componentes
- **Formik & Yup** - Gerenciamento e validação de formulários
- **React Router Hash Link** - Navegação com âncoras
- **RTK Query** - Gerenciamento de requisições API

## API

O projeto se integra com uma API fake hospedada em https://fake-api-tau.vercel.app/api/efood/ que fornece:
- Lista de restaurantes
- Detalhes de restaurantes específicos
- Endpoint de checkout para finalização de pedidos

## Estrutura do Projeto

- `/src/components` - Componentes reutilizáveis da aplicação
- `/src/pages` - Páginas principais da aplicação
- `/src/store` - Configuração e reducers do Redux
- `/src/services` - Serviços e chamadas de API
- `/src/assets` - Recursos estáticos como imagens e ícones

## Scripts Disponíveis

No diretório do projeto, você pode executar:

### `npm start`

Executa o aplicativo no modo de desenvolvimento.\
Abra [http://localhost:3000](http://localhost:3000) para visualizá-lo no navegador.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Inicia o executor de teste no modo de observação interativo.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Compila o aplicativo para produção na pasta `build`.\
Ele agrupa corretamente o React no modo de produção e otimiza a compilação para obter o melhor desempenho.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
