# Çalışan Yönetim Sistemi
- Bu proje, Java'da Nesne Yönelimli Programlama (OOP) prensiplerini kullanarak basit bir çalışan yönetim sistemi oluşturmayı amaçlamaktadır.
- Sistem, çalışan bilgilerini (ad, soyad, maaş, departman) saklayacak, listeleyecek, güncelleyecek ve silecektir.

## Özellikler
- **Çalışan Sınıfı:** Calisan adında bir sınıf oluşturun. Bu sınıfın ad, soyad, maas ve departman gibi özelliklere sahip olması ve bu özelliklere erişim için getter ve setter metodlarını içermesi gerekmektedir.

- **Çalışan Ekleme:** Yeni bir çalışan nesnesi oluşturup sisteme ekleyin.

- **Çalışanları Listeleme:** Tüm çalışanları listeleme.

- **Çalışan Bilgisi Güncelleme:** Belirli bir çalışanın maaşını veya departmanını güncelleyin.

- **Çalışan Silme:** Belirli bir çalışanı sistemden silin.

- **Departmana Göre Çalışanları Listeleme:** Belirli bir departmandaki tüm çalışanları listeleyin.

- **Toplam Maaş Maliyeti:** Tüm çalışanların toplam maaş maliyetini hesaplayın.

## Kullanılan Konular
- Nesne Yönelimli Programlama (Sınıflar, Nesneler)
- Metodlar
- Constructor
- this anahtar kelimesi
- Getter ve Setter Metodları
- ArrayList (Çalışanları saklamak için)
- Koşullu İfadeler
- Döngüler

## Örnek Girdi ve Çıktı

- Senaryo 1: Çalışan Ekleme, Listeleme ve Maaş Güncelleme
### Girdi:
```
1 (Çalışan Ekle)
Ad: Ayşe
Soyad: Yılmaz
Maaş: 50000
Departman: IT
1 (Çalışan Ekle)
Ad: Can
Soyad: Demir
Maaş: 45000
Departman: İnsan Kaynakları
2 (Çalışanları Listele)
3 (Çalışan Güncelle)
Çalışan Adı: Ayşe
Çalışan Soyadı: Yılmaz
Yeni Maaş: 55000
5 (Çıkış)
```
### Beklenen Çıktı
```
--- Çalışan Yönetim Sistemi ---
1. Çalışan Ekle
2. Çalışanları Listele
3. Çalışan Güncelle
4. Çalışan Sil
5. Departmana Göre Çalışanları Listele
6. Toplam Maaş Maliyeti
7. Çıkış
Seçiminiz: 1
Ad: Ayşe
Soyad: Yılmaz
Maaş: 50000
Departman: IT
Çalışan başarıyla eklendi!

--- Çalışan Yönetim Sistemi ---
... (Diğer ekleme çıktısı) ...

--- Çalışan Yönetim Sistemi ---
1. Çalışan Ekle
2. Çalışanları Listele
3. Çalışan Güncelle
4. Çalışan Sil
5. Departmana Göre Çalışanları Listele
6. Toplam Maaş Maliyeti
7. Çıkış
Seçiminiz: 2
--- Çalışan Listesi ---
1. Ad: Ayşe, Soyad: Yılmaz, Maaş: 50000.0, Departman: IT
2. Ad: Can, Soyad: Demir, Maaş: 45000.0, Departman: İnsan Kaynakları

--- Çalışan Yönetim Sistemi ---
1. Çalışan Ekle
2. Çalışanları Listele
3. Çalışan Güncelle
4. Çalışan Sil
5. Departmana Göre Çalışanları Listele
6. Toplam Maaş Maliyeti
7. Çıkış
Seçiminiz: 3
Güncellenecek çalışanın adını girin: Ayşe
Güncellenecek çalışanın soyadını girin: Yılmaz
Güncellenecek alan (maaş/departman): maaş
Yeni Maaş: 55000
Çalışan bilgileri başarıyla güncellendi!

--- Çalışan Yönetim Sistemi ---
1. Çalışan Ekle
2. Çalışanları Listele
3. Çalışan Güncelle
4. Çalışan Sil
5. Departmana Göre Çalışanları Listele
6. Toplam Maaş Maliyeti
7. Çıkış
Seçiminiz: 5
Programdan çıkılıyor...
```

- Senaryo 2: Çalışan Silme ve Departmana Göre Listeleme
### Girdi:
```
1 (Çalışan Ekle)
Ad: Ayşe
Soyad: Yılmaz
Maaş: 50000
Departman: IT
1 (Çalışan Ekle)
Ad: Can
Soyad: Demir
Maaş: 45000
Departman: İnsan Kaynakları
4 (Çalışan Sil)
Çalışan Adı: Ayşe
Çalışan Soyadı: Yılmaz
5 (Departmana Göre Çalışanları Listele)
Departman Adı: İnsan Kaynakları
6 (Toplam Maaş Maliyeti)
7 (Çıkış)
```
### Beklenen Çıktı:
```
--- Çalışan Yönetim Sistemi ---
... (Çalışan ekleme çıktıları) ...

--- Çalışan Yönetim Sistemi ---
1. Çalışan Ekle
2. Çalışanları Listele
3. Çalışan Güncelle
4. Çalışan Sil
5. Departmana Göre Çalışanları Listele
6. Toplam Maaş Maliyeti
7. Çıkış
Seçiminiz: 4
Silinecek çalışanın adını girin: Ayşe
Silinecek çalışanın soyadını girin: Yılmaz
Çalışan başarıyla silindi!

--- Çalışan Yönetim Sistemi ---
1. Çalışan Ekle
2. Çalışanları Listele
3. Çalışan Güncelle
4. Çalışan Sil
5. Departmana Göre Çalışanları Listele
6. Toplam Maaş Maliyeti
7. Çıkış
Seçiminiz: 5
Departman Adı: İnsan Kaynakları
--- İnsan Kaynakları Departmanı Çalışanları ---
1. Ad: Can, Soyad: Demir, Maaş: 45000.0, Departman: İnsan Kaynakları

--- Çalışan Yönetim Sistemi ---
1. Çalışan Ekle
2. Çalışanları Listele
3. Çalışan Güncelle
4. Çalışan Sil
5. Departmana Göre Çalışanları Listele
6. Toplam Maaş Maliyeti
7. Çıkış
Seçiminiz: 6
Toplam Maaş Maliyeti: 45000.0

--- Çalışan Yönetim Sistemi ---
1. Çalışan Ekle
2. Çalışanları Listele
3. Çalışan Güncelle
4. Çalışan Sil
5. Departmana Göre Çalışanları Listele
6. Toplam Maaş Maliyeti
7. Çıkış
Seçiminiz: 7
Programdan çıkılıyor...
```
