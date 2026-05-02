🔐 LOGIN TEST CASES

## TC-LOGIN-001 – Doğru məlumatlarla uğurlu login
- **Priority:** High  
- **Type:** Positive  
- **Precondition:** User artıq qeydiyyatdan keçib  
- **Steps:**
  1. Login səhifəsini aç
  2. Düzgün email daxil et
  3. Düzgün password daxil et
  4. "Login" düyməsini kliklə
- **Expected Result:**
  - User uğurla daxil olur
  - Home səhifəyə redirect olunur
  - Session yaradılır

---

## TC-LOGIN-002 – Yanlış password ilə login
- **Priority:** High  
- **Type:** Negative  
- **Steps:**
  1. Düzgün email daxil et
  2. Səhv password daxil et
  3. Login kliklə
- **Expected Result:**
  - "Invalid credentials" mesajı çıxır
  - Login baş vermir

---

## TC-LOGIN-003 – Boş input sahələri
- **Priority:** High  
- **Type:** Negative  
- **Steps:**
  1. Email və password sahələrini boş saxla
  2. Login kliklə
- **Expected Result:**
  - Validation mesajları göstərilir
  - Request göndərilmir

---

## TC-LOGIN-004 – Yanlış email formatı
- **Priority:** Medium  
- **Type:** Negative  
- **Steps:**
  1. Email sahəsinə `user@` yaz
  2. Password daxil et
  3. Login kliklə
- **Expected Result:**
  - "Invalid email format" mesajı çıxır

---

## TC-LOGIN-005 – Logout sonrası giriş
- **Priority:** Medium  
- **Type:** Positive  
- **Steps:**
  1. Login ol
  2. Logout et
  3. Yenidən login ol
- **Expected Result:**
  - User yenidən uğurla daxil olur
