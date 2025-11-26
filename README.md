# berry12e
"A lightweight Flutter-based educational app prototype designed to enhance classroom engagement and digital learning."
import 'package:flutter/material.dart';

void main() {
  runApp(Berry12eApp());
}

class Berry12eApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Berry12e Classroom App',
      theme: ThemeData(
        primarySwatch: Colors.blue,
      ),
      home: HomePage(),
    );
  }
}

class HomePage extends StatelessWidget {
  final List<String> topics = [
    'Water Cycle',
    'The Sun',
    'Air Pollution',
    'Climate Justice',
    'Math Revision',
  ];

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: Text('Berry12e Learning Hub'),
      ),
      body: ListView.builder(
        itemCount: topics.length,
        itemBuilder: (context, index) {
          return ListTile(
            title: Text(topics[index]),
            leading: Icon(Icons.school),
            onTap: () {
              // You can add navigation to topic details here
            },
          );
        },
      ),
    );
import 'package:flutter/material.dart';

void main() => runApp(Berry12eApp());

class Berry12eApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Berry12e Learning Hub',
      home: HomePage(),
    );
  }
}

class HomePage extends StatelessWidget {
  final List<String> topics = ['Water Cycle', 'Climate Justice', 'Air Pollution'];

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Text('Berry12e Learning Hub')),
      body: ListView.builder(
        itemCount: topics.length,
        itemBuilder: (context, index) {
          return ListTile(
            title: Text(topics[index]),
            leading: Icon(Icons.school),
          );
        },
      ),
    );
  }
}  }
MIT License

Copyright (c) 2025 Francis Maxwell

Permission is hereby granted, free of charge, to any person obtaining a copy of this software...<img width="1024" height="1024" alt="copilot_image_1764197023942" src="https://github.com/user-attachments/assets/371776e5-2d00-4402-9511-e18d67a0f7ce" />
issionopop
