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
