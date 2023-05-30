# CHANGELOG

## 3.0.0 - May 30, 2023

* Updated to require Dart 3 and added the following new lints:
  * deprecated_member_use_from_same_package
  * implicit_reopen
  * invalid_case_patterns
  * matching_super_parameters
  * no_literal_bool_comparisons
  * no_self_assignments
  * type_literal_in_constant_pattern

## 2.1.0 - March 17, 2023

* Updated with latest lints from https://dart-lang.github.io/linter/lints/options/options.html

## 2.0.1 - June 6, 2022

* In the analyzer section, switched from using `implicit-casts: false` and `implicit-dynamic: false` to using `strict-casts: true`, `strict-inference: true`, and `strict-raw-types: true`.
* Removed `close_sinks: ignore` from the analyzer error section.

## 2.0.0 - May 28, 2022

* Bumped the minimum required Dart SDK version to 2.17
* Added the following lints:
  * avoid_final_parameters
  * conditional_uri_does_not_exist
  * secure_pubspec_urls
  * sized_box_shrink_expand
  * sort_constructors_first
  * use_late_for_private_fields_and_variables
  * use_super_parameters
* Updated `package:flutter_lints` dependency to version 2.0.1, which added the following lints:
  * depend_on_referenced_packages
  * library_private_types_in_public_api
  * no_leading_underscores_for_library_prefixes
  * no_leading_underscores_for_local_identifiers
  * null_check_on_nullable_type_parameter
  * prefer_interpolation_to_compose_strings
  * sort_child_properties_last
  * unnecessary_constructor_name
  * unnecessary_late
  * unnecessary_null_aware_assignments
  * unnecessary_nullable_for_final_variable_declarations
  * use_build_context_synchronously

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
