
SIGN UP TEST CASES

## TC-SIGNUP-001 – Uğurlu qeydiyyat
- **Priority:** High  
- **Type:** Positive  
- **Steps:**
  1. Sign up səhifəsinə keç
  2. Ad daxil et
  3. Email daxil et
  4. Password daxil et
  5. Sign up kliklə
- **Expected Result:**
  - Yeni user yaradılır
  - Login və ya home səhifəyə yönləndirilir

---

## TC-SIGNUP-002 – Mövcud email ilə qeydiyyat
- **Priority:** High  
- **Type:** Negative  
- **Steps:**
  1. Sistemdə mövcud email daxil et
  2. Digər sahələri doldur
  3. Sign up kliklə
- **Expected Result:**
  - "Email already exists" mesajı çıxır

---

## TC-SIGNUP-003 – Zəif password
- **Priority:** Medium  
- **Type:** Negative  
- **Steps:**
  1. Password sahəsinə `12345` yaz
  2. Qeydiyyatı tamamla
- **Expected Result:**
  - Password validation error çıxır

---

## TC-SIGNUP-004 – Boş sahələrlə qeydiyyat
- **Priority:** High  
- **Type:** Negative  
- **Steps:**
  1. Heç bir sahəni doldurma
  2. Sign up kliklə
- **Expected Result:**
  - Required field error-lar göstərilir
