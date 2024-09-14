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

  static Map<String,List<String>> medical = {
    'currentRoles' : ['Anaesthetics ACCS 4'],
    'completedRoles' : ['Medical School', 'FY1', 'FY2', 'Medical Education FY3', 'Primary FRCA'],
    'toGo' : ['ICM trainee', 'Anaesthetics Trainee', 'CCT'],
    'nerdyInterests' : ['Physiology', 'Pre-hospital Medicine', 'Evidence Based Medicine', 'Machine Learning', 'Personal Finance'],
  };

  static List<String> ongoingProjects = [
    'Personal finance app aimed at doctors',
    'Cohort study into ECG criteria for LVH',
    'Tinkering with raspberry pi cluster',
    'Home automation using and contributing to HomeAssistant'
  ]

}

final me = new Me()
```
