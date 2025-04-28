# Pokedex-Info
Um aplicativo Flutter moderno que funciona como um Pokédex, permitindo aos usuários navegar, pesquisar e favoritar Pokémon. O aplicativo conta com integração com o Firebase para autenticação de usuários e persistência de dados.

## Recursos
- 🔐 Autenticação do Usuário (Cadastro/Login)
- 🔍 Buscar Pokémon
- ⭐ Sistema de Pokémon Favoritos
- 💾 Persistência de dados offline
- 🎨 Interface de Usuário com Material Design Moderno
- 🔄 Atualizações em tempo real com o Firebase
- 📱 Design Responsivo

## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado:
- [Flutter](https://flutter.dev/docs/get-started/install) (>=3.0.0)
- [Dart](https://dart.dev/get-dart) (>=3.0.0)
- [Firebase CLI](https://firebase.google.com/docs/cli)
- [Git](https://git-scm.com/)

## Project Structure

```
lib/
├── models/
│   └── pokemon_model.dart
├── providers/
│   └── pokemon_provider.dart
├── screens/
│   ├── home_screen.dart
│   ├── login_screen.dart
│   ├── favorites_screen.dart
│   └── pokemon_detail_screen.dart
├── services/
│   ├── auth_service.dart
│   ├── firebase_service.dart
│   ├── pokemon_api_service.dart
│   ├── storage_service.dart
│   └── services.dart
└── main.dart
```

## Dependencies

- `provider`: State management
- `firebase_core`: Firebase core functionality
- `firebase_auth`: Firebase authentication
- `cloud_firestore`: Cloud Firestore for data storage
- `firebase_storage`: Firebase Storage
- `http`: API requests
- `shared_preferences`: Local data storage


## Começando

1. Clone o repositório:
 ```bash
git clone <repository-url>
cd pokemon_app
```
2. Instale as dependências:
```bash
flutter pub get
```
3. Configure o Firebase:
```bash
npm install -g firebase-tools
```
- Log in to Firebase:
```bash
firebase login
```
- Instale FlutterFire CLI:
```bash
dart pub global activate flutterfire_cli
```
- Configure Firebase :
```bash
flutterfire configure
```
4. Execute o aplicativo:
```bash
flutter run
```
![telainicial_pokemon](https://github.com/user-attachments/assets/bda7ad6c-af9d-48b1-b6bb-1dff903c3df7)


![telacriação_pokemon](https://github.com/user-attachments/assets/133576d7-1100-4228-9c9d-2403be209531)

![telainicialpokemon_pokemon](https://github.com/user-attachments/assets/1029ffef-a1b2-4c7a-923a-0f3166b3bb19)

![telafavoritos_pokemon](https://github.com/user-attachments/assets/63565925-e7d2-425e-95f5-51a29a39d9b1)

![telasobrepokemon_01](https://github.com/user-attachments/assets/98b6d6a8-4437-4406-82f7-e356365936e7)

![telasobrepokemon_02](https://github.com/user-attachments/assets/d0f109bd-a92d-458d-a2ec-27f50df0626c)

![tela_sair](https://github.com/user-attachments/assets/e52bf158-cee8-4cc2-b4fd-a6e4f3761c8b)
