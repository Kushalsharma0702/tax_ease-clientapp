# TaxEase Client App

Flutter client app (web, Android, iOS) for filing personal tax returns, part of the TaxEase tax platform.

## Done so far

- Feature-based architecture in `lib/`: `core`, `features` and `shared`
- Feature modules: auth, onboarding, dashboard, documents, filing, tax forms, notifications, profile and settings
- Tax questionnaire data models updated to match the Excel templates (see `QUESTIONNAIRE_2_UPDATE_STATUS.md`)
- API contract documented in `api_documentation.md` (register, login, OTP request and verify, current user, file upload)
- Project structure notes in `PROJECT_STRUCTURE.md`

## Stack

Flutter and Dart, flutter_bloc, go_router, get_it and injectable, Dio and Retrofit, Hive, Lottie and Rive animations, reactive_forms

## Run locally

```bash
flutter pub get
flutter run -d chrome
```

## Related repositories

- [taxease_admin](https://github.com/Kushalsharma0702/taxease_admin): admin dashboard
- [Taxify](https://github.com/Kushalsharma0702/Taxify): AI tax platform front end

## Future scope

- Finish the remaining tax form flows and connect them to the live backend
- OTP login and document upload end to end with the production API
- Automated tests (widget and integration) and CI builds
- Accessibility pass, localisation, and release builds for the app stores
