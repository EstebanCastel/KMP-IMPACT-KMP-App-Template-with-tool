### Dependabot impact companion

- **Dependency:** `io.ktor`
- **Version change:** `2.3.7` → `3.5.0`
- **Risk:** **HIGH**
- **Recommendation:** Hold merge until impacted files are reviewed and targeted regression checks pass.
- **Static impact:** 11 files (3 direct / 8 transitive-or-expect-actual)
- **UI impact:** 7 screens
- **Dynamic analysis:** skipped
- **Full report:** generated as static artifact/site in `output/report/`

### Top impacted files

| File | Relation | Source set | RLOC | MCC |
|------|----------|------------|------|-----|
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/data/MuseumApi.kt` | direct | commonMain | 23 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/di/Koin.kt` | direct | commonMain | 45 | 1 |
| `/tmp/output/phase1/before/tools/kmp-impact-analyzer/tests/fixtures/sample_kotlin/CommonModule.kt` | direct | common | 8 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/detail/DetailScreen.kt` | transitive | commonMain | 133 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/list/ListScreen.kt` | transitive | commonMain | 92 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/App.kt` | transitive | commonMain | 44 | 3 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/list/ListViewModel.kt` | transitive | commonMain | 13 | 1 |
| `/tmp/output/phase1/before/androidApp/src/main/kotlin/com/jetbrains/kmpapp/MuseumApp.kt` | transitive | main | 9 | 1 |
| `/tmp/output/phase1/before/shared/src/commonMain/kotlin/com/jetbrains/kmpapp/screens/detail/DetailViewModel.kt` | transitive | commonMain | 9 | 1 |
| `/tmp/output/phase1/before/tools/kmp-impact-analyzer/tests/fixtures/sample_kotlin/AppModule.kt` | transitive | common | 7 | 1 |
