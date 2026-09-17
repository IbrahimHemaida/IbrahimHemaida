# Ibrahim Hemaida

**Senior Mobile Engineer and Mobile Team Lead · Android (Kotlin, Jetpack Compose) · Flutter · AI-native engineering**

Ibrahim Hemaida is a senior mobile engineer and team lead with 13+ years building Android and Flutter applications for healthcare, hospitality, and high-traffic consumer products. He works on AI-assisted engineering workflows and builds open-source tooling that keeps AI-generated mobile code architecturally correct.

*Name is also written as Ibraheem Hmeda.*

[Articles on dev.to](https://dev.to/ibrahimhemaida) · [Medium](https://medium.com/@ibraheem.hmeda) · [LinkedIn](https://linkedin.com/in/ibrahimhemaida) · [ibraheem.hmeda@gmail.com](mailto:ibraheem.hmeda@gmail.com)

---

## Open Source

### [mobile-engineering-skills](https://github.com/IbrahimHemaida/mobile-engineering-skills)

A plugin that reviews Kotlin/Android and Flutter code for the problems static analysis does not catch: layer violations, broken module boundaries, state management that looks fine locally but breaks under real usage, and architectural drift in AI-generated code.

AI coding assistants write code that is locally correct and globally wrong. A linter reads one file at a time, so it stays silent. This plugin encodes the review layer that sits above it.

<!-- اكتب هنا وصف سطرين لكل من Android-Scope و Mobile-Architecture-Ecosystem، أو احذف السطرين لو مش جاهزين للعرض -->

### [Android-Scope](https://github.com/IbrahimHemaida/Android-Scope)

*(وصف قصير)*

### [Mobile-Architecture-Ecosystem](https://github.com/IbrahimHemaida/Mobile-Architecture-Ecosystem)

*(وصف قصير)*

---

## Writing

I publish on how AI changes mobile engineering practice, and on the architecture work that AI still cannot do for you.

- [AI Writes Locally Correct Code, Which Is Why Your Linter Is Silent](https://dev.to/ibrahimhemaida/ai-writes-locally-correct-code-which-is-why-your-linter-is-silent-2d1b): eight failure patterns AI assistants produce in Kotlin and Dart, sorted into four levels by the tooling that can actually catch them.

More at [dev.to/ibrahimhemaida](https://dev.to/ibrahimhemaida).

---

## Technical Toolkit

* **Native Android:** Kotlin, Jetpack Compose, Coroutines, Flow, Dagger Hilt
* **Cross-Platform:** Flutter (BLoC, Provider, Riverpod), Kotlin Multiplatform (KMM)
* **Architecture:** Clean Architecture, SOLID principles, feature-driven modularization
* **Quality:** detekt with type resolution, Konsist, mutation testing, unit and integration coverage
* **Leadership:** team management, code review, mentoring, agile delivery
* **Accessibility:** WCAG 2.1 AA, patient-facing clinical UI, cognitive and motor accessibility patterns

| Category | Technology |
| :--- | :--- |
| **Frameworks** | Flutter, Jetpack Compose, KMM |
| **DI / State** | BLoC, Riverpod, Hilt, Koin |
| **Networking** | Retrofit, Dio, Ktor |
| **Database** | Room, Hive, SQLDelight |

---

## Case Studies

### Nabed Connect and Nabed TV: healthcare IoT ecosystem

* **The challenge:** building a nationwide healthcare platform with 99.9% content availability across restricted clinical networks.
* **The solution:** an offline-first system with local persistence and MQTT-based device synchronization, plus a custom kiosk launcher with hardware-level MAC activation.
* **Impact:** device activation time down 60%, multi-patient session handling improved 30% through a WCAG accessibility-first tablet UI redesign.

### RD Labs: AI assistant and caller ID

* **The challenge:** modernizing a high-traffic application with 3M+ users while holding crash rates down and keeping the UI smooth.
* **The solution:** led a full migration to Hilt, Coroutines, and MVVM Clean Architecture with modular configurations, and integrated on-device NLP for real-time processing.
* **Impact:** crash rate down 15% (Firebase Crashlytics), average UI jank down 40% (Android Profiler and Systrace).

### Savvy: smart hotel automation

* **The challenge:** automating guest experiences over IoT controls without making the interface harder to use.
* **The solution:** integrated PMS and VingCard SDKs over Bluetooth and NFC, wrapped in a UI designed to stay usable for guests with mobility limitations.
* **Impact:** automated guest workflows across 5+ luxury properties, service request resolution 35% faster.

---

## How I Work

* **Modular architecture:** features isolated so teams can work in parallel.
* **Code quality:** SOLID in practice, not on paper, backed by real test coverage.
* **Scale:** systems that grow past a million users without accumulating architectural debt.
* **AI with a review layer:** AI writes a lot of the code now. The job is making sure the architecture survives it.

---

## Currently

Open to remote Senior and Lead mobile roles.

**Get in touch:** [LinkedIn](https://linkedin.com/in/ibrahimhemaida) · [ibraheem.hmeda@gmail.com](mailto:ibraheem.hmeda@gmail.com)
