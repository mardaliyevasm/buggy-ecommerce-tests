# PROFILE MODULU TEST CASES

---

## Test Case 10

| Field | Məlumat |
|---|---|
| Test Case ID | TC_PROFILE_001 |
| Modul | Profile |
| Test Case Adı | İstifadəçi profil məlumatlarını görə bilir |
| Priority | Medium |
| Type | Positive |
| Preconditions | User login olmalıdır |
| Steps | 1. Profile səhifəsinə keç |
| Test Data | Valid user |
| Expected Result | İstifadəçi məlumatları görünməlidir |
| Status | Not Run |

---

## Test Case 11

| Field | Məlumat |
|---|---|
| Test Case ID | TC_PROFILE_002 |
| Modul | Profile |
| Test Case Adı | Profil məlumatları yenilənir |
| Priority | Medium |
| Type | Positive |
| Preconditions | User login olmalıdır |
| Steps | 1. Profile edit et <br> 2. Save klik et |
| Test Data | New username |
| Expected Result | Yeni məlumat yadda saxlanmalıdır |
| Status | Not Run |

---

## Test Case 12

| Field | Məlumat |
|---|---|
| Test Case ID | TC_PROFILE_003 |
| Modul | Profile |
| Test Case Adı | Login olmadan profile giriş mümkün olmamalıdır |
| Priority | High |
| Type | Negative |
| Preconditions | User login olmamalıdır |
| Steps | 1. Profile URL aç |
| Test Data | — |
| Expected Result | Login səhifəsinə yönləndirilməlidir |
| Status | Not Run |
