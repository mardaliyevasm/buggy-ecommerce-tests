
👤 PROFILE TEST CASES

## TC-PROFILE-001 – Profil məlumatlarına baxış
- **Priority:** High  
- **Type:** Positive  
- **Steps:**
  1. Login ol
  2. Profile səhifəsinə keç
- **Expected Result:**
  - User məlumatları düzgün göstərilir

---

## TC-PROFILE-002 – Profil update
- **Priority:** High  
- **Type:** Positive  
- **Steps:**
  1. Ad və ya digər məlumatı dəyiş
  2. Save kliklə
- **Expected Result:**
  - Dəyişikliklər yadda saxlanılır

---

## TC-PROFILE-003 – Logout
- **Priority:** High  
- **Type:** Positive  
- **Steps:**
  1. Logout kliklə
- **Expected Result:**
  - User sistemdən çıxır
  - Login səhifəsinə yönləndirilir

---

## TC-PROFILE-004 – Unauthorized access
- **Priority:** High  
- **Type:** Negative  
- **Steps:**
  1. Login olmadan profile URL aç
- **Expected Result:**
  - Login səhifəsinə redirect olunur
