# LOGIN MODULE TEST CASES

---

## Test Case 1

| Field | Məlumat |
|---|---|
| Test Case ID | TC_LOGIN_001 |
| Modul | Login |
| Test Case Adı | Düzgün email və şifrə ilə login |
| Priority | High |
| Type | Positive |
| Preconditions | İstifadəçi qeydiyyatdan keçmiş olmalıdır |
| Steps | 1. Login səhifəsini aç <br> 2. Email daxil et <br> 3. Password daxil et <br> 4. Login düyməsinə klik et |
| Test Data | test@gmail.com / Test123 |
| Expected Result | İstifadəçi uğurla hesabına daxil olur |
| Status | Not Run |

---

## Test Case 2

| Field | Məlumat |
|---|---|
| Test Case ID | TC_LOGIN_002 |
| Modul | Login |
| Test Case Adı | Yanlış şifrə ilə login olmamalıdır |
| Priority | High |
| Type | Negative |
| Preconditions | İstifadəçi mövcud olmalıdır |
| Steps | 1. Login səhifəsini aç <br> 2. Düzgün email daxil et <br> 3. Yanlış password daxil et <br> 4. Login klik et |
| Test Data | test@gmail.com / 12345 |
| Expected Result | Error mesajı görünməlidir |
| Status | Not Run |

---

## Test Case 3

| Field | Məlumat |
|---|---|
| Test Case ID | TC_LOGIN_003 |
| Modul | Login |
| Test Case Adı | Boş sahələrlə login mümkün olmamalıdır |
| Priority | Medium |
| Type | Negative |
| Preconditions | Login səhifəsi açıq olmalıdır |
| Steps | 1. Heç nə daxil etmə <br> 2. Login düyməsinə klik et |
| Test Data | Empty fields |
| Expected Result | Validation mesajı görünməlidir |
| Status | Not Run |

