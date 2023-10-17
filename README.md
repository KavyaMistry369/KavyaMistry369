
``` dart

class FlutterDeveloper {
  String name = "Kavya Mistry";
  List<String> skills = ["C", "C++", "Dart", "Flutter", "SQL", "PHP", "Figma", "Firebase", "Prompt Engineering"];
  String passion = "Creating amazing mobile experiences";

  FlutterDeveloper(this.name);

  void introduceYourself() {
    print("Hello, I'm $name, a passionate Flutter developer.");
    print("My skills include:");
    skills.forEach((skill) {
      print("- $skill");
    });
    print("I'm driven by my passion for $passion.");
    print("Let's build some incredible apps together!");
  }
}

void main() {
  final developer = FlutterDeveloper("Kavya Mistry");
  developer.introduceYourself();
}

```




