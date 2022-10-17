# Camus Lint Rules

[![pub package](https://img.shields.io/pub/v/camus_lints.svg)](https://pub.dev/packages/camus_lints)

This repository contains a set of lint rules for [Flutter] apps, packages,
and plugins to encourage good coding practices.

This package is built on top of Flutter's lints from package:flutter_lints.

## Usage

1. Depend on this package as a **dev_dependency** by running
  `flutter pub add --dev camus_lints`.
2. Create an `analysis_options.yaml` file at the root of the package (alongside
   the `pubspec.yaml` file) and `include: package:camus_lints/camus.yaml`
   from it.

## Reference

- [Effective Dart](https://dart.dev/guides/language/effective-dart/style)
- [Flutter Style Guide](https://github.com/flutter/flutter/wiki/Style-guide-for-Flutter-repo)
- [Flutter Lints](https://pub.dev/packages/flutter_lints)
