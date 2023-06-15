# Flutter Monorepo Template
Flutter Monorepo is a centralized repository that enables cross-platform app development using Flutter in an efficient and highly scalable manner. This monorepo provides a structured development approach and allows development teams to share business logic, resources, and components across Android, iOS, and web applications.

## Tech Stacks
- [Flutter](https://flutter.dev/)
- [Melos](https://melos.invertase.dev/)

## How to use
1. Use template or clone this repository
2. Makesure melos by `dart pub global activate melos` or skip this step if already installed
3. execute `melos bootstrap`
4. Done. Run example app by `cd apps/example` then `flutter run`

## File Structure
```
- apps
  - app_01
  - app_02
  - app_03
- packages
  - uikit
  - utils
  - other_reusable_code
```
In this file structure, there are two main directories:

1.  `apps`: This directory contains specific Flutter applications such as `app_01`, `app_02`, and `app_03`. Each application directory can contain code and resources related to that specific application, such as user interface components, business logic, and application configurations.
2.  `packages`: This directory contains reusable packages for Flutter application development. Some example packages that might be included are:
    -   `uikit`: A package that includes reusable UI components such as buttons, cards, or other UI elements. This enables consistent user interfaces across applications developed within the monorepo.
    -   `utils`: A package that includes utility functions or helper tools that can be reused across multiple applications, such as helper functions for data manipulation, network connections, or image processing.
    -   `other_reusable_code`: Other packages that contain reusable code, such as specific utilities, constants, or algorithms used in multiple applications within the monorepo.

This file structure allows for the separation of business logic and reusable components into separate packages, facilitating code reusability and easier maintenance across multiple applications within the monorepo.

Please note that the above structure is just a starting template, and you can customize it according to your project's needs and preferences.

