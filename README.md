
````markdown
##🚀 **Boost Your Flutter Release Builds Using `--split-per-abi`**

When you're ready to release your Flutter app, build size matters. In this post, learn how `flutter build apk --release --split-per-abi` helps reduce APK size and improve performance.

---

## 🧠 What is `--split-per-abi`?

Different Android devices use different CPU architectures:

- `armeabi-v7a`
- `arm64-v8a`
- `x86_64` (emulators)

Using `--split-per-abi` generates smaller APKs for each architecture instead of one fat APK.

---

## ⚙️ Command

```bash
flutter build apk --release --split-per-abi
````

> Output directory: `build/app/outputs/flutter-apk/`

---

## 📦 Example APKs Generated:

* `app-armeabi-v7a-release.apk`
* `app-arm64-v8a-release.apk`
* `app-x86_64-release.apk`

---

## 📉 Size Comparison

| APK Type      | Approx Size |
| ------------- | ----------- |
| Fat APK       | \~70 MB     |
| `armeabi-v7a` | \~30 MB     |
| `arm64-v8a`   | \~34 MB     |

---

## 🔗 Backlinks & Further Reading

* 📖 Official Flutter Docs: [Build and release APK](https://docs.flutter.dev/deployment/android#build-an-apk)
* 📚 More Flutter guides on [TechyCodex](https://www.techycodex.com)
* 🔧 Full source code: [GitHub Repo](https://github.com/TechyCodex/flutter-apk-split-guide)

---

## 💬 About TechyCodex

**TechyCodex** is a dev-focused publication sharing tutorials, dev tools, and coding tips for Flutter, Firebase, and full-stack projects.

👉 Visit: [https://www.techycodex.com](https://www.techycodex.com)

---

*Written by Parikshit Verma for [TechyCodex](https://www.techycodex.com).*

```

---
