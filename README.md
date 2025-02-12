# Complete Flutter Course Bundle - eCommerce App

This is the official repo for this course:

- [Complete Flutter Course Bundle](https://codewithandrea.com/courses/complete-flutter-bundle/)

This will include a full-stack eCommerce app using Flutter & Firebase:

![eCommerce App Preview](/.github/images/ecommerce-app-preview.png)

A Flutter web preview of the app can be found here:

- [Flutter Web Demo](https://my-shop-ecommerce-stg.web.app/)

## Documentation & FAQ

This project includes a documentation website that can be found here:

- [Complete Flutter Course Bundle - Documentation](https://docs.page/bizz84/complete-flutter-course)

## Flutter Foundations - Course Syllabus

### 1. Intro & Project Overview

1. What you will learn in this course
2. Section overview
3. VSCode Shortcuts, Extensions & Settings for Flutter development
4. Join the Slack Channel
5. Course Project on GitHub
6. Download the Starter Project & `pubspec.yaml` overview
7. eCommerce app overview
8. Code walkthrough: project structure
9. Exploring the codebase with the Widget Inspector (DevTools)
10. UI Design Principles: Composition & Reusable Widget Classes
11. Useful Widgets for Responsive Design
12. App Localization

### 2. Navigation with GoRouter

1. Section Intro
2. Limitations of Navigator 1.0
3. GoRouter installation & initial setup with `MaterialApp.router`
4. Routes, sub-routes and navigation
5. `GoRouterHelper` Extension and `pageBuilder`
6. Adding some additional routes
7. Routing by **path** vs routing by **name**
8. Routing with parameters
9. GoRouter error handling
10. Navigating with **go** vs **push**
11. Adding the remaining routes
12. How to pop a route with GoRouter
13. Nested Navigation
14. Wrap up

### 3. Flutter App Architecture

1. Section Intro
2. Popular App Architectures: MVC, MVP, MVVM, Clean Architecture, Bloc
3. Riverpod App Architecture with the Controller-Service-Repository Pattern
4. Project Structure: Feature-first vs Layer-first
5. The Repository Pattern and the Data Layer
6. Implementing the "fake" products repository as a singleton
7. Working with Future and Stream-based APIs
8. Wrap Up

### 4. State Management with Riverpod - Part 1 (Product Listings)

1. Section Intro
2. Introduction to Riverpod
3. Riverpod installation and setup
4. Creating our first provider
5. Reading providers with `ConsumerWidget` and `Consumer`
6. Working with `FutureProvider`, `StreamProvider`, and `AsyncValue`
7. Testing `AsyncValue` by adding a delay
8. The `family` modifier
9. The `autoDispose` modifier + advanced data caching options
10. Creating a reusable `AsyncValueWidget` helper
11. Wrap Up + Exercise

### 5. State Management with Riverpod - Part 2 (Authentication Flow)

1. Section intro
2. Implementing a fake authentication repository
3. Creating repositories using abstract classes (optional)
4. Intro: a reactive in-memory store with RxDart
5. Implementing the `InMemoryStore` with RxDart
6. Using the `InMemoryStore` in the `FakeAuthRepository`
7. Accessing the `FakeAuthRepository` with `ref.read()` in the `AccountScreen`
8. Creating our first controller using `StateNotifier`
9. Using the `StateNotifier` inside the `AccountScreen` widget
10. Listening to provider state changes with `ref.listen()`
11. Bug-fix for `Navigator.pop`
12. The `AsyncValue.guard` method
13. Adding an `AsyncValue` extension method
14. Using the `authStateChangesProvider` in `HomeAppBar`
15. Intro to the email & password sign-in screen
16. How to generate immutable state classes in Dart
17. Using `AsyncValue` inside `EmailPasswordSignInState`
18. Implementing the `EmailPasswordSignInController`
19. Using the `EmailPasswordSignInController` in the widget class
20. Bug fix + filtering state updates with `select()`
21. GoRouter redirects
22. GoRouter: the `refreshListenable` argument
23. Fixing the checkout flows after changes to refreshListenable (advanced)
24. Wrap Up

### 6. Automated Testing - Part 1

1. Section Intro
2. Introduction to Automated Testing and the Testing Pyramid
3. Getting started with automated testing
4. Writing the first unit test + adding `toString()` and equality implementations
5. Test matchers and working with methods that throw exceptions
6. Fixing the `getProduct()` method and updating the unit tests
7. Working with groups and testing Futures and Streams
8. Adding an optional delay to the `FakeProductsRepository`
9. How to generate a Flutter test coverage report in VSCode
10. Testing the `FakeAuthRepository` (part 1)
11. Testing the `FakeAuthRepository` (part 2) + advanced stream matchers
12. Mocks vs Fakes + installing the mocktail package
13. Testing the `AccountScreenController` (part 1)
14. Testing the `AccountScreenController` (part 2) + working with mocks
15. Testing the `AccountScreenController` (part 3) + type matchers
16. Testing the `EmailPasswordSignInController` with acceptance criteria + working with test predicates (advanced)
17. Testing the `EmailPasswordSignInController` (part 2)
18. Testing lifecycle methods (`setUp`, `tearDown`, `setUpAll`, `tearDownAll`)
19. Adding a test workflow to automate testing with GitHub Actions
20. Wrap up

### [LICENSE: MIT](LICENSE.md)