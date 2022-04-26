# MAIN.DART

import 'package:bandeiras/ucrania.dart';
import 'package:flutter/material.dart';
import 'dinamarca.dart';
import 'russia.dart';
import 'barbados.dart';
import 'libano.dart';
import 'estadosunidos.dart';

class MyApp extends StatelessWidget {
  const MyApp({Key? key}) : super(key: key);

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Estadosunidos(),
    );
  }
}

void main(List<String> args) {
  runApp(MyApp());
}
