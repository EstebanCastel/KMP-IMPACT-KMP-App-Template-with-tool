### Dependabot impact companion

- **Dependency:** `org.jetbrains.kotlin.multiplatform`
- **Version change:** `1.9.24` → `2.3.21`
- **Risk:** **HIGH**
- **Recommendation:** Hold merge until impacted files are reviewed and targeted regression checks pass.
- **Static impact:** 10 files (7 direct / 3 transitive-or-expect-actual)
- **UI impact:** 6 screens
- **Dynamic analysis:** skipped
- **Full report:** generated as static artifact/site in `output/report/`

### Top impacted files

| File | Relation | Source set | RLOC | MCC |
|------|----------|------------|------|-----|
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/App.kt` | direct | commonMain | 44 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/di/Koin.kt` | direct | commonMain | 45 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/data/MuseumRepository.kt` | direct | commonMain | 21 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/data/MuseumStorage.kt` | direct | commonMain | 21 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/data/MuseumObject.kt` | direct | commonMain | 17 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/list/ListViewModel.kt` | direct | commonMain | 13 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/detail/DetailViewModel.kt` | direct | commonMain | 9 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/detail/DetailScreen.kt` | transitive | commonMain | 133 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/list/ListScreen.kt` | transitive | commonMain | 92 | 3 |
| `/tmp/output/phase1/before/androidApp/src/main/kotlin/com/jetbrains/kmpapp/MuseumApp.kt` | transitive | main | 9 | 1 |
