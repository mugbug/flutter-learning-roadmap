# Flutter Roadmap

## Task list

* [ ] `very_good create my_personal_project`
* [ ] Go to [BloC tutorials](https://bloclibrary.dev/#/fluttertodostutorial) and try to implement one of those following the [Bloc docs](https://bloclibrary.dev/#/fluttertodostutorial)
* [ ] Push your code to a GitHub repo and try adding some workflows to run automated tests and linter on pull requests

## Resources

Project starting point:

- [fvm to install flutter and switch between versions](https://fvm.app/)
- [https://pub.dev/packages/very_good_cli](https://pub.dev/packages/very_good_cli) use this instead of the default `flutter create`

Foundation:

- [Decoding Flutter](https://www.youtube.com/watch?v=33_0ABjFJUU&list=PLjxrf2q8roU1fRV40Ec8200rX6OuQkmnl)

Stage Management

- [BloC docs](https://bloclibrary.dev/#/gettingstarted) & [tutorials](https://bloclibrary.dev/#/fluttertodostutorial)
- [Why we [vgv] use flutter_bloc for state management](https://verygood.ventures/blog/why-we-use-flutter-bloc)

Navigation/routing

- [go_router](https://pub.dev/packages/go_router)

Code architecture

- [Are you saying that my code is boring? Thank you!](https://verygood.ventures/blog/boring-code-part-1) & [Very good layered architecture in Flutter](https://verygood.ventures/blog/very-good-flutter-architecture)

User Interface

- Discover some useful widgets at [Widget Of the Week](https://www.youtube.com/hashtag/widgetoftheweek)
- [Flutter Widget Livebook](https://flutter-widget.live/basics/introduction)
- [Flutter Gallery](https://gallery.flutter.dev/#/)

Testing

- [Widget Testing [2022]](https://www.youtube.com/watch?v=aReBbQgLjtk)
- [Other testing resources](https://verygood.ventures/blog/flutter-testing-resources)
- Libraries:
  - Unit & widget & mocking: [mocktail](https://github.com/felangel/mocktail)
  - Snapshot (golden) testing: [alchemist](https://github.com/Betterment/alchemist)
  - UI/e2e: [maestro](https://maestro.mobile.dev/)

CI/CD

- [fastlane](https://docs.fastlane.tools/)
  - Android: [tbd]
  - iOS: [Tutorial](https://joshuamdeguzman.com/continuous-delivery-for-flutter-using-fastlane-and-github-actions-pt-3-ios/)
    - Create a Deploy Key for the certificates repo instead of a github's personal access token
    - You could use a [dotenv file](https://docs.fastlane.tools/best-practices/keys/#dotenv) instead of adding a lot of secrets
- [reusable GitHub Actions workflows](https://github.com/VeryGoodOpenSource/very_good_workflows)

Monorepo

- [melos](https://melos.invertase.dev/)

Tooling

- [DevTools](https://www.youtube.com/watch?v=nq43mP7hjAE)
- [File templates with BrickHub + Mason](https://brickhub.dev/)

Code examples

- [Google I/O 2021 Photo Booth](https://github.com/flutter/photobooth)
- [Flutter News Toolkit example](https://github.com/flutter/news_toolkit/tree/main/flutter_news_example)

Other

- [Flutter's youtube channel](https://www.youtube.com/c/flutterdev/playlists) has an infinite amount of good content teaching more about Flutter.
- [Flutter Vikings 2022 conf videos](https://www.youtube.com/watch?v=gn1F7GClECY&list=PL4dBIh1xps-EWXK28Qn9kiLK9-eXyqKLX)
- [DartFrog: dart on backend](https://github.com/verygoodopensource/dart_frog)
