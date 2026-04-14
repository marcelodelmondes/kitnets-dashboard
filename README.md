<<<<<<< HEAD
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

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

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
=======
# 🏠 KitNet OS — Dashboard de Gestão

Dashboard premium para gestão de kitnets com dark mode, avatares pixel art e gráficos interativos.

## 🚀 Setup Rápido

### 1. Instalar dependências
```bash
npm install
```

### 2. Configurar Supabase (opcional)
```bash
cp .env.example .env.local
# Edite .env.local com suas credenciais do Supabase
```

Execute o SQL em `src/lib/supabase.js` no Supabase SQL Editor para criar as tabelas.

### 3. Rodar localmente
```bash
npm start
```

### 4. Deploy na Vercel
```bash
# Via CLI:
npx vercel --prod

# Ou conecte o repositório no dashboard da Vercel
# Adicione as variáveis de ambiente no painel da Vercel:
# REACT_APP_SUPABASE_URL
# REACT_APP_SUPABASE_ANON_KEY
```

## 🔐 Modo Editor
- PIN padrão: **1234**
- Altere `EDITOR_PIN` em `src/lib/data.js`
- Somente o editor pode adicionar/remover transações

## 🎨 Funcionalidades
- 📊 Dashboard com 4 gráficos (Recharts)
- 💰 Cards animados com contador
- 🏢 Gestão de kitnets com status em tempo real
- 👥 Avatares pixel art 8-bit dos sócios
- 📈 Gráfico de payback com break-even automático
- 🔒 Sistema de PIN para controle de edição
- 🗄️ Integração Supabase pronta

## 🛠 Stack
- React 18 + Tailwind CSS
- Recharts para gráficos
- Supabase para backend
- Fontes: Rajdhani + DM Sans + JetBrains Mono
>>>>>>> a9b97365ee728fdf9a0965e238a46aac99c28d21
