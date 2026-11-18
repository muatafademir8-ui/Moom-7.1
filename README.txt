MOOM 6.2 - ACIK ARA SAHNELI SURUM

Bu paket onceki kaynak kodu guncellemelerini tek surumde birlestirir.

OZELLIKLER
- Acilis ara sahnesi: Jack arabayla gelir, durur, aciktigini soyler, arabadan iner ve binaya girer. X ile ara sahne atlanabilir.
- 7 bolum: Zindan, Hastane, Fabrika, Depo, Kanalizasyon, Laboratuvar, Cati Kati.
- Dusman oldugunde gomulu PCM olum sesi calar.
- Zombi olum animasyonunda dikey boyu azalip yatay gorunume gecer.
- Olmus zombiler siyah ceset sprite'i olarak yerde kalir; ekran karartilmaz.
- R1 (PSP_CTRL_RTRIGGER) pompalı tufek ile cift tabanca arasinda gecis yapar.
- Cift tabanca iki adet 3D tabanca modeliyle gosterilir.
- X veya Kare ates eder; L1 sola yan yurume olarak kalir.
- Her iki silah ortak mermi sayacini kullanir.

KONTROLLER
- Analog: hareket ve saga/sola donus
- D-pad: alternatif hareket/donus
- L1: sola yan yurume
- R1: silah degistir
- Daire: kosma
- X veya Kare: ates
- START: olumden sonra bolumu yeniden baslatir; bolum bitince sonraki bolume gecer

DERLEME
main.c ve Makefile dosyalarini PSP SDK projenize koyun ve GitHub Actions/PSPSDK ile EBOOT.PBP derleyin.

DOGRULAMA NOTU
Bu ortamda PSP SDK bulunmadigindan EBOOT.PBP derlemesi ve PPSSPP testi yapilamadi.
Kaynak kodda birlestirme ve temel sembol kontrolleri yapildi. Sesin PSP cihazinda duyulmasi,
PSP ses API'sinin calismasina ve onceki ses kaydinin dogru olmasina baglidir.
