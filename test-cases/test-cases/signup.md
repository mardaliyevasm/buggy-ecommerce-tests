# SIGN IN MODULE TEST CASES

---

## Test Case 4

| Field | Məlumat |
|---|---|
| Test Case ID | TC_SIGNIN_001 |
| Modul | Sign In |
| Test Case Adı | Yeni istifadəçi uğurla qeydiyyatdan keçir |
| Priority | High |
| Type | Positive |
| Preconditions | Sayt açıq olmalıdır |
| Steps | 1. Sign in səhifəsinə keç <br> 2. Username daxil et <br> 3. Email daxil et <br> 4. Password daxil et <br> 5. Register klik et |
| Test Data | usertest / user@gmail.com / Test123 |
| Expected Result | Hesab uğurla yaradılır |
| Status | Not Run |

---

## Test Case 5

| Field | Məlumat |
|---|---|
| Test Case ID | TC_SIGNIN_002 |
| Modul | Sign In |
| Test Case Adı | Boş məlumatlarla qeydiyyat mümkün olmamalıdır |
| Priority | High |
| Type | Negative |
| Preconditions | Sign in səhifəsi açıq olmalıdır |
| Steps | 1. Sahələri boş saxla <br> 2. Register düyməsinə klik et |
| Test Data | Empty |
| Expected Result | Validation mesajları görünməlidir |
| Status | Not Run |

---

## Test Case 6

| Field | Məlumat |
|---|---|
| Test Case ID | TC_SIGNIN_003 |
| Modul | Sign In |
| Test Case Adı | Eyni email ilə ikinci dəfə qeydiyyat olmamalıdır |
| Priority | Medium |
| Type | Negative |
| Preconditions | Email artıq sistemdə mövcuddur |
| Steps | 1. Mövcud email daxil et <br> 2. Digər məlumatları yaz <br> 3. Register klik et |
| Test Data | existing@gmail.com |
| Expected Result | “Email already exists” mesajı görünməlidir |
| Status | Not Run |
