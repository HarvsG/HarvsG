### Welcome to me.dart

<!--
**HarvsG/HarvsG** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


```dart 
class Me extends Human with Doctor, Developer {
  static String username = 'HarvsG';
  static String website = 'www.codingdoctor.co.uk'
  static String contact = 'doctor@codingdoctor.co.uk'

  static List<Languages> canCode = [
    Python,
    R,
    Dart,
    Flutter,
    Javascript
    ];

  static Map<String,dynamic> medical = {
    'currentRole' : 'Medical Education',
    'completedRoles' : ['Medical School', 'FY1', 'FY2'],
    'toGo' : ['ACCS Anaesthetics', 'ICM trainee', 'Anaesthetics Trainee', 'CCT'],
    'interests' : ['Physiology','Pre-hospital Medicine', 'Evidence Based Medicine'],
  };

  static List<String> ongoingProjects = [
    'GitHub clone for clinical research',
    'Cohort study into ECG criteria for LVH',
    'Tinkering with raspberry pi cluster',
    'Energy usage and production monitoring with raspberry pi'
  ]

}

final me = new Me()
```
