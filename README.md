## SEO-friendly URL Generator

**Install**
```
  composer require necmettinavci/seourl
```
**Usage**

```
  <?php
      require_once "./vendor/autoload.php";
      use necmettinavci\SeoUrl\SeoUrl;
      echo SeoUrl::convert('Türkçe İçerik Başlığı Örnek!'); 
      // Output: turkce-icerik-basligi-ornek

```