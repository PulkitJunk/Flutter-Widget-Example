import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatefulWidget {
  const MyApp({super.key});

  @override
  State<MyApp> createState() => _MyAppState();
}

class _MyAppState extends State<MyApp> {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Draggable',
      home: Scaffold(
        appBar: AppBar(
          title: Text('Draggable'),
        ),
        body: DraggableScrollableSheet(
          initialChildSize: 0.4,
          minChildSize: 0.2,
          maxChildSize: 0.6,
          builder: (context, ScrollController) {
            return Container(
              color: Colors.blue,
              child: SingleChildScrollView(
                controller: ScrollController,
                child: Center(
                  child: Placeholder(), // enter code at placeholder 
                ),
              ),
            );
          },
        ),
      ),
    );
  }
}
