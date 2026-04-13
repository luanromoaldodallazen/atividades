trabalho:
integrantes(1): Luan Romoaldo Chagas Dallazen

# ETAPA 1:
é um projeto onde precisa fazer um jogo estilo termo

# ETAPA 2:
flutter create birdle --empty

# ETAPA 3:
void main*( {
  runApp(const MainApp());
}

class MainApp extends StatelessWidget {
  const MainApp({super.key});

  @override
Widget build(BuildContext context) {
    return const MaterialApp(
      home: Scaffold(
        body: Center(
          child: Text('Hello World!'),
        ),
      ),
    );
  }
}

# ETAPA 4:
cd birdle
flutter run -d chrome

# ETAPA 5:
child: Text('Meu app Birdle'),
