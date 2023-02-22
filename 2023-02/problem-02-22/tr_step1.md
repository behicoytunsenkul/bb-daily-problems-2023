## Problem - Dosya İşlemleri   
Bu senaryo içerisinde sizlere tahsis edilen makinelere klasör oluşturmanızı ve klasörlerin içerisine aşağıdaki talimatlar gereğince dosya işlemleri uyguladığınız bir senaryo hazırlamanız istenmektedir.

### Talimatlar
1.  `/home/ogrenci/` adında bir dizin oluşturunuz ve o dizin altında "`dosya_islemleri`" adında yeni bir klasör oluşturunuz.
2.  `/home/ogrenci/dosya_islemleri` dizini altında "dosya1.txt" adında bir dosya oluşturunuz. İçerisine "BB" yazınız.
3. `/home/ogrenci/dosya_islemleri` dizini altında "dosya2.txt" adında bir dosya oluşturunuz. İçerisine "`Daily Coding 2023`" yazınız.
4. Aynı klasör içerine bu iki dosyayı birleştirerek "dosya3.txt" adında bir dosya oluşturunuz.
5. "dosya3.txt" dosyasının içerisindeki "`Daily Coding 2023`" yazısını "`Daily Coding 2023 - OK`" olarak değiştiriniz.
6. İşlemleri tamamladıktan sonra "Kontrol et" butonuna basınız ve senaryoyu tamamlayınız.

### Başarılı Çıktı
```echo
[root@node1 ~]$ cat /home/ogrenci/dosya_islemleri/dosya3.txt
BBDaily Coding 2023 - OK
```

### Faydalı Linkler
- [Linux Dosya İşlemleri](https://tr.wikibooks.org/wiki/Linux_%C4%B0%C5%9Fletim_Sistemi/Linux_Komutlar%C4%B1/Dosya_ve_klas%C3%B6r_komutlar%C4%B1/)
