Life Hack or Urban Myth?

Module Code and Name: IMAD5112 – Introduction to Mobile Application Development
Student Name: Dimpho Ayanda Kgohloane 
Student Number: ST10527228

Video Presentation

Video link: https://youtu.be/TftEnqdZYg8?si=ENmb7H87PpUhcCKN
File link: C:/users/lab_services_student/AndroidStudioProjects/Lifehackorurbanmythapp/.git/

Purpose of the App

Life hacks and internet rumors are everywhere. Users often struggle to distinguish between genuine productivity tips and urban myths that have gone viral. “Life Hack or Urban Myth?” is a native Android flashcard quiz app built with Kotlin code in Android Studio that helps users test their common sense and learn useful and safe shortcuts.

The app presents 10 statements one at a time. The user must decide whether each is a real “Life Hack (True)” or an “Urban Myth (False)”. After all questions, a personalized score and review are provided.


App Features

Feature Description 

Welcome Screen - Brief description and a "Start" button 
Flashcard Quiz - 10 statements with Hack / Myth buttons 
Live Feedback - Immediate correct/incorrect feedback per answer 
Score Screen - Total score with personalized feedback message 
Review Screen - Scrollable list of all questions and correct explanations 
Play Again - Return to welcome screen to restart 

Design Considerations

The app uses a simple “single-activity-per-screen” with four Activity classes:

MainActivity        →   Welcome Screen
QuestionActivity    →   Flashcard Question Screen (loop)
ScoreActivity       →   Score & Feedback Screen
ReviewActivity      →   Review All Answers Screen

Application Logic

The quiz loop in QuestionActivity uses:
- An array of triples to store each question (statement, correct boolean, explanation)
- An integer index (“currentIndex”) incremented with each "Next" press
- A “when” expression in `ScoreActivity` to map score ranges to personalized messages

GitHub & GitHub Actions

Version Control

This project uses GitHub for version control:
- A new repository was created for this project
- The repository was initialized with this README file
- All source code was committed and pushed to the `main` branch
- Regular commits were made after completing each feature

This ensures the app compiles and all tests pass on every commit — not just on the developer's local machine.


References

[1] Google, "Start another activity," *Android Developers*, 2024. [Online]. Available: https://developer.android.com/training/basics/firstapp/starting-activity. [Accessed: Apr. 2026].

[2] Google, "Intents and Intent Filters," *Android Developers*, 2024. [Online]. Available: https://developer.android.com/guide/components/intents-filters. [Accessed: Apr. 2026].

[3] Google, "Layouts," *Android Developers*, 2024. [Online]. Available: https://developer.android.com/develop/ui/views/layout/declaring-layout. [Accessed: Apr. 2026].

[4] Google, "App manifest overview," *Android Developers*, 2024. [Online]. Available: https://developer.android.com/guide/topics/manifest/manifest-intro. [Accessed: Apr. 2026].

[5] Google, "Configure your build," *Android Developers*, 2024. [Online]. Available: https://developer.android.com/build. [Accessed: Apr. 2026].

[6] JetBrains, "Kotlin documentation," *Kotlin*, 2024. [Online]. Available: https://kotlinlang.org/docs/home.html. [Accessed: Apr. 2026].

[7] JetBrains, "Control flow: if, when, for, while," *Kotlin*, 2024. [Online]. Available: https://kotlinlang.org/docs/control-flow.html. [Accessed: Apr. 2026].

[8] JetBrains, "Arrays," *Kotlin*, 2024. [Online]. Available: https://kotlinlang.org/docs/arrays.html. [Accessed: Apr. 2026].

[9] GitHub, "GitHub Actions documentation," *GitHub Docs*, 2024. [Online]. Available: https://docs.github.com/en/actions. [Accessed: Apr. 2026].

[10] GitHub Marketplace, "Automated Build Android App with Github Action," 2024. [Online]. Available: https://github.com/marketplace/actions/automated-build-android-app-with-github-action. [Accessed: Apr. 2026].

[11] IIE IMAD5112, "build.yml example," *GitHub*, 2024. [Online]. Available: https://github.com/IMAD5112/Github-actions/blob/main/.github/workflows/build.yml. [Accessed: Apr. 2026].

[12] Google, "ScrollView," *Android Developers*, 2024. [Online]. Available: https://developer.android.com/reference/android/widget/ScrollView. [Accessed: Apr. 2026].


This project was completed as part of IMAD5112 – Introduction to Mobile Application Development Assignment 2, The Independent Institute of Education (IIE), 2026.


