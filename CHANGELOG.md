# CHANGELOG

## 1.0.1

* Updated to include:
```
analyzer:
  strong-mode:
    implicit-casts: false
    implicit-dynamic: false

  errors:
    close_sinks: ignore
    missing_required_param: error
    missing_return: error

  exclude:
    - /**/generated_plugin_registrant.dart
    - /**/.test_coverage.dart
```

## 1.0.0

* Initial release.
