### Dependabot impact companion

- **Dependency:** `org.jetbrains.compose`
- **Version change:** `1.6.0` → `1.11.0`
- **Risk:** **MEDIUM**
- **Recommendation:** Review the directly impacted files and run focused smoke tests before merging.
- **Static impact:** 6 files (2 direct / 4 transitive-or-expect-actual)
- **UI impact:** 5 screens
- **Dynamic analysis:** skipped
- **Full report:** generated as static artifact/site in `output/report/`

### Top impacted files

| File | Relation | Source set | RLOC | MCC |
|------|----------|------------|------|-----|
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/detail/DetailScreen.kt` | direct | commonMain | 133 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/EmptyScreenContent.kt` | direct | commonMain | 22 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/list/ListScreen.kt` | transitive | commonMain | 92 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/App.kt` | transitive | commonMain | 44 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/di/Koin.kt` | transitive | commonMain | 45 | 1 |
| `/tmp/output/phase1/before/androidApp/src/main/kotlin/com/jetbrains/kmpapp/MuseumApp.kt` | transitive | main | 9 | 1 |
