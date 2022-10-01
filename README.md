# Flutter Roadmap

## Task list

* [ ] `very_good create my_personal_project`
* [ ] Go to [BloC tutorials](https://bloclibrary.dev/#/fluttertodostutorial) and try to implement one of those following the [Bloc docs](https://bloclibrary.dev/#/fluttertodostutorial)

## Resources

Project starting point:

- [https://pub.dev/packages/very_good_cli](https://pub.dev/packages/very_good_cli) use this instead of the default `flutter create`

Stage Management

- [BloC docs](https://bloclibrary.dev/#/gettingstarted) & [tutorials](https://bloclibrary.dev/#/fluttertodostutorial)
- [Why we [vgv] use flutter_bloc for state management](https://verygood.ventures/blog/why-we-use-flutter-bloc)

Code architecture

- [Are you saying that my code is boring? Thank you!](https://verygood.ventures/blog/boring-code-part-1) & [Very good layered architecture in Flutter](https://verygood.ventures/blog/very-good-flutter-architecture)

Testing

- [Widget Testing [2022]](https://www.youtube.com/watch?v=aReBbQgLjtk)
- [Other testing resources](https://verygood.ventures/blog/flutter-testing-resources)

CI/CD

- [fastlane](https://docs.fastlane.tools/)
  - Android: [tbd]
  - iOS: [Tutorial](https://joshuamdeguzman.com/continuous-delivery-for-flutter-using-fastlane-and-github-actions-pt-3-ios/)
    - Create a Deploy Key for the certificates repo instead of a github's personal access token
    - You could use a [dotenv file](https://docs.fastlane.tools/best-practices/keys/#dotenv) instead of adding a lot of secrets
- [reusable GitHub Actions workflows](https://github.com/VeryGoodOpenSource/very_good_workflows)
