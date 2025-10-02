
import 'package:flutter/material.dart';

void main() {
runApp(const MyApp());
}

class MyApp extends StatelessWidget {
const MyApp({super.key});

@override
Widget build(BuildContext context) {
return MaterialApp(
debugShowCheckedModeBanner: false,
home: Scaffold(
body: Center(
child: Column(
mainAxisAlignment: MainAxisAlignment.center,
children: const [
CircleAvatar(
radius: 60,
backgroundImage: NetworkImage("https://i.pravatar.cc/150?img=3"),
),
SizedBox(height: 15),
Text(
"Trung Chien",
style: TextStyle(
fontSize: 24,
fontWeight: FontWeight.bold,
),
),
Text(
"Ho Chi Minh, Viet Nam",
style: TextStyle(
fontSize: 16,
color: Colors.grey,
),
),
],
),
),
),
);
}
}
=======
# homework-firstweek
homework firstweek
>>>>>>> a6294489b8b889d3f16f5eb82fcf0271a1c442d0
