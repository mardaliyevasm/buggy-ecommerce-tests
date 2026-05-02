 🛒 CART (SƏBƏT) TEST CASES

## TC-CART-001 – Məhsulu səbətə əlavə etmə
- **Priority:** High  
- **Type:** Positive  
- **Steps:**
  1. Home səhifəyə keç
  2. Hər hansı məhsulu seç
  3. "Add to cart" kliklə
- **Expected Result:**
  - Məhsul səbətə əlavə olunur
  - Cart icon update olunur

---

## TC-CART-002 – Eyni məhsulun sayını artırma
- **Priority:** Medium  
- **Type:** Positive  
- **Steps:**
  1. Eyni məhsulu 2 dəfə əlavə et
- **Expected Result:**
  - Quantity artır (məsələn: 2 olur)

---

## TC-CART-003 – Məhsulu səbətdən silmə
- **Priority:** High  
- **Type:** Positive  
- **Steps:**
  1. Cart səhifəsinə keç
  2. "Remove" kliklə
- **Expected Result:**
  - Məhsul səbətdən silinir

---

## TC-CART-004 – Boş səbət
- **Priority:** Low  
- **Type:** Edge Case  
- **Steps:**
  1. Cart səhifəsinə keç (boş halda)
- **Expected Result:**
  - "Cart is empty" mesajı çıxır

---

## TC-CART-005 – Login olmadan səbət
- **Priority:** Medium  
- **Type:** Edge Case  
- **Steps:**
  1. Login olmadan məhsul əlavə et
- **Expected Result:**
  - Guest cart işləyir və ya login tələb olunur
