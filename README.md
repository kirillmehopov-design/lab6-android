# Lab 6 - User Registration & Form Validation

Flutter registration screen with real-time and submit-time validation.

## Features

- Full Name: required
- Email: required, valid email format
- Password: required, at least 6 characters, hidden input
- Confirm Password: must match
- Role: Student / Teacher / Developer dropdown
- Terms and Conditions: required checkbox
- Errors appear below invalid inputs
- Successful registration shows a SnackBar and logs non-sensitive registration data

## Run

Requires Flutter SDK.

1. Open a terminal in this folder.
2. Run `flutter create .` to generate the platform directories if they are missing.
3. Run `flutter pub get`.
4. Run `flutter run`.

All app UI and behavior are implemented in `lib/main.dart`.
