Login / Sign in Test Cases
TC-LOGIN-001 – Doğru məlumatlarla login
Precondition: User qeydiyyatdan keçib
Steps:
Login səhifəsinə keç
Email və password daxil et
Login kliklə
Expected: User uğurla daxil olur, home səhifəyə yönləndirilir
TC-LOGIN-002 – Yanlış password
Steps: düzgün email + səhv password
Expected: Error mesaj (“Invalid credentials”)
TC-LOGIN-003 – Boş inputlar
Steps: email və password boş qoy
Expected: Validation error göstərilir
TC-LOGIN-004 – Email formatı səhv
Steps: test@ kimi email daxil et
Expected: “Invalid email format”
