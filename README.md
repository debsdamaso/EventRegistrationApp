# Event Registration App

Este projeto é um aplicativo React Native para simular o registro de eventos. O fluxo de navegação entre as telas depende da passagem e compartilhamento de props entre os componentes.

## Estrutura do Projeto

- **`src/components/InputField.tsx`**: Componente para entrada de texto.
- **`src/screens/HomeScreen.tsx`**: Tela inicial para inserir o nome do evento.
- **`src/screens/EventDetailsScreen.tsx`**: Tela para inserir detalhes adicionais sobre o evento.
- **`src/screens/SummaryScreen.tsx`**: Tela para exibir todas as informações coletadas sobre o evento.
- **`App.tsx`**: Configuração da navegação do aplicativo.

## Pré-requisitos

Certifique-se de ter os seguintes softwares instalados:

- [Node.js](https://nodejs.org/) (versão 18.x ou superior)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- [Android Studio](https://developer.android.com/studio) ou [Xcode](https://developer.apple.com/xcode/) (para emulação)

## Configuração do Projeto

1. **Criar um Novo Projeto Expo com TypeScript:**

   npx expo init EventRegistrationApp --template blank-typescript

2. **Navegar para o diretorio**
   
   cd EventRegistrationApp

3. **Instalar dependencias**
   
   Se houver aviso de pacote imcompativel, usar: expo doctor --fix-dependencies

4. **Iniciar servidor de desenvolvimento**

   npx expo start
