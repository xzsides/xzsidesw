# resources/ nasıl çalışır

Bu klasördeki dosyalar artık script ile değil, doğrudan templates.html
içine yazılarak listelenir — site tamamen statiktir, JavaScript kullanmaz.

Yeni bir şablon eklemek için:

1. Dosyayı resources/template/ klasörüne at.
2. templates.html içine, mevcut örneklerdeki gibi bir ".tpl-card" bloğu
   ekle: başlık, kısa açıklama, indirme bağlantısı ve dosyanın tam metni.
3. Kaydet, git push'la.

Bu şekilde sayfa hem bir sunucudan hem de dosyayı bilgisayarında çift
tıklayıp file:// ile açtığında da sorunsuz çalışır.
