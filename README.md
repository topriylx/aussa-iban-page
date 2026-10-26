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
5. Alan adınızın DNS yönetiminde yalnızca web sitesi için olan eski Lovable kayıtlarını GitHub Pages'in gösterdiği kayıtlarla değiştirin. E-posta için kullanılan MX/TXT kayıtlarına dokunmayın.
6. GitHub Pages ayarlarında HTTPS hazır olduğunda **Enforce HTTPS** seçeneğini açın.

GitHub Pages'i ücretsiz kullanmak için depo herkese açık olmalıdır. Site zaten bu IBAN bilgilerini herkese gösterdiğinden, depodaki kaynak dosyaları da herkese açık olur. Alan adının yenileme ücreti mevcut alan adı sağlayıcınıza aittir; bu yöntem ayrıca bir hosting ücreti gerektirmez.

GitHub'ın [özel alan adı kurulumu](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site) ve [DNS kayıtları](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site) yönergeleri.
