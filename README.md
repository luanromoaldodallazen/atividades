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
2. criação do flutter pelo terminal usando flutter create
3. estrutura do codigo com mainapp, widget, return, home, body, child
4. executando o jogo pelo terminal usando cd birdle e flutter run
5. mudando o texto usando hot reload
6. resumo do projeto
7. iniciando o jogo com o widget
