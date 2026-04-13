trabalho:
integrantes(1): Luan Romoaldo Chagas Dallazen

import 'package:flutter/material.dart';

void main() {
  runApp(const MainApp());
}

class MainApp extends StatelessWidget {
  const MainApp({super.key});

  @override
  Widget build(BuildContext context) {
    return const MaterialApp(
      home: Scaffold(
        body: Center(
          child: Text('Meu jogo'),
        ),
      ),
    );
  }
}

terminal:
cd birdle
flutter run -d chrome


# EXPLICAÇÕES
1. projeto de jogo estilo termo
2. criação do flutter pelo terminal
3. estrutura do codigo
4. executando o jogo pelo terminal
5. mudando o texto
6. resumo do projeto
7. iniciano o jogo
