# App Expo

Aplicativo de estudos em **React Native** desenvolvido com **Expo**. O projeto contém uma tela inicial simples e serve como base para exercícios e evolução de interfaces móveis.

## Tecnologias

- Expo SDK 54
- React 19
- React Native 0.81
- React Native Paper
- Expo Vector Icons

## Estrutura

O código do aplicativo está na pasta `app-expo/`:

- `App.js`: componente principal;
- `src/pages/HomePage.js`: tela inicial;
- `assets/`: ícones e imagens do aplicativo;
- `app.json`: configurações do Expo;
- `package.json`: dependências e comandos.

## Como executar

### Pré-requisitos

- Node.js;
- npm;
- Expo Go no celular ou um emulador Android/iOS.

### Instalação

```bash
git clone https://github.com/AntonioRubens77/app-expo.git
cd app-expo/app-expo
npm install
npm start
```

Depois, escolha uma das opções apresentadas pelo Expo:

- escanear o QR Code com o Expo Go;
- executar no Android com `npm run android`;
- executar no iOS com `npm run ios`;
- executar no navegador com `npm run web`.
