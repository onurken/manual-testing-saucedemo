Bug Reports – SauceDemo Website

BUG001 – Login error message not clear
Environment: Chrome / Windows  
Steps to Reproduce:
1. Open login page
2. Enter wrong username
3. Enter wrong password
4. Click Login

Expected Result:
Clear error message should be shown to user

Actual Result:
Error message is not clear enough


Priority: Low  
Status: Open

---

BUG002 – Cart badge not updated
Environment: Chrome / Windows  
Steps to Reproduce:
1. Login with valid credentials
2. Add a product to cart

Expected Result:
Cart icon badge should update and show product count

Actual Result:
Cart badge does not update immediately


Priority: Medium  
Status: Open

---

BUG003 – Checkout without first name
Environment: Chrome / Windows  
Steps to Reproduce:
1. Login
2. Add product to cart
3. Go to checkout
4. Leave first name field empty
5. Click Continue

Expected Result:
Error message should be displayed

Actual Result:
No error message displayed

 
Priority: High  
Status: Open


----


BR-02 – Geçersiz E-posta Formatı Kabul Ediliyor

Özet:  
İletişim formunda e-posta alanına geçersiz formatta veri girilmesine rağmen
form başarıyla gönderilmektedir.

Ortam:  
- Uygulama: İletişim Formu Demo  
- URL: https://onurken.github.io/manual-testing-saucedemo/  
- Tarayıcı: Google Chrome  
- İşletim Sistemi: Windows 10  

Ön Koşul:  
Kullanıcı iletişim formu sayfasına erişmiş olmalıdır.

Tekrar Adımları:
1. İletişim formu sayfası açılır  
2. Ad Soyad alanı doldurulur  
3. E-posta alanına geçersiz formatta veri girilir (örn: abc123)  
4. Mesaj alanı doldurulur  
5. Gönder butonuna tıklanır  

Beklenen Sonuç:  
Sistem geçersiz e-posta formatını kabul etmemeli ve
kullanıcıya uygun bir hata mesajı göstermelidir.

Gerçekleşen Sonuç:  
Geçersiz e-posta formatına rağmen
“Form başarıyla gönderildi” mesajı gösterilmektedir.

Öncelik: 
-Orta

Ciddiyet:
-Orta

