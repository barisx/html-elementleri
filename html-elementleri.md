
HTML elementleri bir tag ismi ile başlayıp onu bitirmesiyle de sonlanır.

```html
<tag-adi> Basladi ve simdi bitirelim. </tag-adi>
```

HTML elementleri daha önceden belirlenmiş isimlerle nitelendirilirler. 
Mesela sayfanın baslığı için "title" kullanıyoruz.

```html
<title> Bu bir baslik </title>
```

HTML elementleri tag adı farketmeksizin iç içe olabilir.

```html
<title> HTML <title>
  <article> Makale
    <div>

      <h2> HTML Temelleri </h2>
      <p> HTML bir dil değildir. </p>

    </div>
  </article>
```

HTML elementlerini kapatmayı unutmayalım.
Haydi şimdi hata yapalım.

```html
<html>
  <body>

    <p> Bu bir paragraf
    <p> Bu bir paragraf

  </body>
</html>
```

Şimdi de doğrusunu yazalım:


```html
<html>
  <body>

    <p> Bu bir paragraf </p>
    <p> Bu bir paragraf </p>

  </body>
</html>
```

Bazı elementler değer içermez. Mesela `<br>` direkt yeni satıra geçer.

```html
<p> Paragraf 1. satırda <br> devamı 2. satırda.</p>

```

HTML taglarında büyük veya küçük harf farketmez.
`<P>` ile `<p>` aynıdır.
