# expo-google-app-auth

> Source code for the deprecated `expo-google-app-auth` package.

Expo Google App Auth API wrapped the deprecated `expo-app-auth` package and added a JS API for authenticating with Google using the web authentication (web was not supported). We've replaced this package with [`expo-auth-session/providers/google`](https://docs.expo.dev/guides/authentication/#google) which works on iOS, Android, and web. The new solution is much more flexible and light-weight as it reuses primitives in your app rather than adding new native code.

- Documentation: [SDK 44 Google AppAuth](https://github.com/expo/expo/blob/sdk-44/docs/pages/versions/v44.0.0/sdk/google.md).
