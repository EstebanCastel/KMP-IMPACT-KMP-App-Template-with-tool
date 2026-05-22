### Dependabot impact companion

- **Dependency:** `io.insert-koin`
- **Version change:** `3.5.6` → `4.2.1`
- **Risk:** **MEDIUM**
- **Recommendation:** Review the directly impacted files and run focused smoke tests before merging.
- **Static impact:** 5 files (3 direct / 2 transitive-or-expect-actual)
- **UI impact:** 4 screens
- **Dynamic analysis:** skipped
- **Full report:** generated as static artifact/site in `output/report/`

### Top impacted files

| File | Relation | Source set | RLOC | MCC |
|------|----------|------------|------|-----|
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/detail/DetailScreen.kt` | direct | commonMain | 133 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/list/ListScreen.kt` | direct | commonMain | 92 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/di/Koin.kt` | direct | commonMain | 45 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/App.kt` | transitive | commonMain | 44 | 3 |
| `/tmp/output/phase1/before/androidApp/src/main/kotlin/com/jetbrains/kmpapp/MuseumApp.kt` | transitive | main | 9 | 1 |
