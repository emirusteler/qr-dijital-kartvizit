# QR Dijital Kartvizit

Bilgilerinizi girip **QR kod** ve **çevrim içi link** ile dijital kartvizit paylaşın. QR ile rehbere eklenir veya link ile tarayıcıda kartvizit açılır.

## Çevrim içi yayın (GitHub Pages)

1. Bu projeyi GitHub’a push edin (bağlantıyı zaten yaptıysanız `git push` yeterli).
2. Repo sayfasında **Settings** → **Pages**.
3. **Source**: "Deploy from a branch" seçin.
4. **Branch**: `main` (veya kullandığınız varsayılan dal), **Folder**: `/ (root)`.
5. **Save** deyip birkaç dakika bekleyin.
6. Yayın adresi: `https://<kullanici-adiniz>.github.io/<repo-adiniz>/`

Bu adres açıldığında kartvizit sayfanız çevrim içi olur. Paylaşım linki ve "Çevrim içi kartvizit linki" QR’ı da bu adrese göre çalışır.

## Ne yapmanız gerekenler

1. **Sayfayı açın**  
   GitHub Pages adresinizi veya yerelde `index.html` dosyasını açın.

2. **Formu doldurun**  
   Ad Soyad (zorunlu), ünvan, firma, e-posta, telefon, web, adres (isteğe bağlı).

3. **"QR Kodu Güncelle"**  
   Sağda kartvizit önizlemesi, rehbere ekleme QR’ı ve çevrim içi link QR’ı oluşur.

4. **Paylaşın**  
   - **"Paylaşım linkini kopyala"**: Linki kopyalayıp mesaj/e-posta ile gönderin; tıklayan kartviziti tarayıcıda görür.  
   - **Çevrim içi link QR’ı**: Bu QR’ı tarayan kişi aynı linki açar, kartvizitiniz yüklenir.  
   - **Rehbere ekleme QR’ı**: Tarandığında kişi rehbere eklenir (vCard).

Link paylaşıldığında URL’de bilgileriniz parametre olarak gider. **Linki açan kişi sadece kartviziti görür** (düzenleme formu ve QR alanları görünmez). Siz kendi kartvizitinizi düzenlemek için sayfanın ana adresini (parametresiz) açın.

- **Telefon**: +90 sabit gelir; numarayı "555 555 55 55" formatında girin.
- **Web sitesi**: https:// yazmasanız da program otomatik ekler.
- **WeChat**: İsteğe bağlı WeChat kullanıcı adı alanı vardır.
- **Dil**: Türkçe, English, 中文 seçenekleri sayfa üstündedir.
- **Logo**: "Logo (görsel linki)" alanına logonuzun URL’sini yapıştırın. Logoyu GitHub’a eklemek için repoya bir dosya (örn. `logo.png`) yükleyin; görselin adresi `https://kullanici.github.io/repo-adi/logo.png` olur. Bu linki forma yapıştırın.

## Dosyalar

- `index.html` – Tek sayfa uygulama (form, önizleme, QR’lar).
- `.nojekyll` – GitHub Pages’in Jekyll kullanmaması için (statik site).
- `README.md` – Bu dosya.
