# Projeto Flutter Web com Firebase

Este projeto é um exemplo de aplicação Flutter para Web utilizando Firebase Authentication e Firebase Storage. Siga os passos abaixo para configurar e executar o projeto corretamente.

## ⚙️ Pré-requisitos

- Flutter instalado ([guia oficial](https://docs.flutter.dev/get-started/install))
- Conta no Firebase e acesso ao [Firebase Console](https://console.firebase.google.com/)
- Google Chrome instalado

## 🔥 Configuração do Firebase

1. Acesse o [Firebase Console](https://console.firebase.google.com/) e crie um novo projeto.
2. Adicione um novo app do tipo **Web** ao projeto.
3. Copie as configurações do Firebase Web (apiKey, authDomain, etc.).
4. No seu projeto Flutter, localize o arquivo `web/index.html` ou um arquivo de configuração Firebase (`firebase_options.dart` se estiver usando `flutterfire`) e insira suas credenciais.
5. Habilite os métodos de autenticação desejados em **Authentication > Sign-in method** no painel do Firebase (ex: Email/senha).

> **Dica:** Para gerar o arquivo `firebase_options.dart`, instale o CLI do FlutterFire:
```bash
dart pub global activate flutterfire_cli
flutterfire configure
