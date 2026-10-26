# Aussa.co ödeme sayfası

Lovable'daki ödeme sayfasının bilgileri ve görünümüne göre hazırlanmış, tek dosyalı statik sitedir. Sunucu, veritabanı, ücretli servis veya ek paket gerektirmez.

## İçerik

- `index.html`: Site ve IBAN kopyalama düğmesi
- `favicon.svg`: Tarayıcı sekmesindeki küçük logo
- `CNAME`: Özel alan adı (`aussa.co`)

## Ücretsiz yayınlama

GitHub Pages, ücretsiz GitHub hesabında herkese açık bir depoyla kullanılabilir. Bu sayfa için depoda `index.html`, `favicon.svg` ve `CNAME` dosyaları yeterlidir.

1. GitHub'da boş ve **public** bir depo açın.
2. Bu klasördeki üç dosyayı deponun ana dizinine yükleyin.
3. Depodaki **Settings → Pages** bölümünde yayın kaynağını `main` dalı ve `/ (root)` olarak seçin.
4. Pages ayarlarında özel alan adını `aussa.co` olarak kaydedin.
5. Alan adınızın DNS yönetiminde web sitesi için kullanılan eski Lovable `A`/`AAAA` kayıtlarını aşağıdaki GitHub Pages kayıtlarıyla değiştirin. E-posta için kullanılan `MX`/`TXT` kayıtlarına dokunmayın.

   - `A` / `@` → `185.199.108.153`
   - `A` / `@` → `185.199.109.153`
   - `A` / `@` → `185.199.110.153`
   - `A` / `@` → `185.199.111.153`
   - `AAAA` / `@` → `2606:50c0:8000::153`
   - `AAAA` / `@` → `2606:50c0:8001::153`
   - `AAAA` / `@` → `2606:50c0:8002::153`
   - `AAAA` / `@` → `2606:50c0:8003::153`

6. DNS yayılımı 24 saate kadar sürebilir. GitHub Pages ayarlarında DNS doğrulaması tamamlanınca **Enforce HTTPS** seçeneğini açın.

GitHub Pages'i ücretsiz kullanmak için depo herkese açık olmalıdır. Site zaten bu IBAN bilgilerini herkese gösterdiğinden, depodaki kaynak dosyaları da herkese açık olur. Alan adının yenileme ücreti mevcut alan adı sağlayıcınıza aittir; bu yöntem ayrıca bir hosting ücreti gerektirmez.

GitHub'ın [özel alan adı kurulumu](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) ve [DNS kayıtları](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) yönergeleri.
