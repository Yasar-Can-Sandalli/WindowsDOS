
<img width="180" height="160" align="left" style="float: top-left; margin: 0 15px 0 0;" alt="MS-DOS logo" src="Images\msdos-logo.png">   

# Windows DOS Komutlarına Giriş 💻
<p>
  MS-DOS, bilgisayarlar üzerinde temel işlemleri komut satırında gerçekleştirebilmek için kullanılan bir işletim sistemidir. Bu rehberde, bazı temel MS-DOS komutlarını ve kullanım şekillerini bulacaksınız.
</p>

</br>

## `dir`

**Klasör İçeriğini Listeleme**  
Bu komut, içinde bulunduğunuz dizindeki dosyaları ve klasörleri listeler. En sonda bulduğu sonuçların sayısını en aşağıda döndürür

```dos
dir
```
![dir_komutu](Images/dir.png)


* `dir /a` parametresi ile gizli dosyalar dahil tüm dosyalari listeleyebilirisiniz

```dos
dir /a
```

![dir_komutu](Images/dira.png)
![dir_komutu](Images/diraD.png)

<!--dir a-->

* `dir /ah` parametresi ile sadece gizli doyaları ve klasörleri listeleyebilirsiniz

```dos
dir /ah
```
![dir_komutu](Images/dirah.png)

<!--dir b-->

* `dir /b` parametresi ile sadece dosya ve klasör adlarını görebilirsiniz; ek bilgi içermez ve listelemede minimum bilgi sağlar.

```dos
dir /b
```
![dir_komutu](Images/dirb.png)

<!--dir d-->

* `dir /d` Dosya ve klasör adlarını geniş biçimde, köşeli parantezler içinde ekranda listeler

```dos
dir /d
```
![dir_komutu](Images/dird.png)