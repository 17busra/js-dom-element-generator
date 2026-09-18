# JavaScript Dinamik Form Elemanı Üretici ⚙️

Bu proje, JavaScript kullanılarak DOM (Document Object Model) üzerinde dinamik olarak HTML elemanlarının nasıl yaratılacağını ve yönetileceğini gösteren bir uygulamadır. 

**Projenin İşlevleri:**
* Kullanıcıdan üretilecek eleman sayısını ve tipini (Checkbox veya Radio) alır.
* Girilen değere göre sanal HTML elementleri (`input`, `label`) oluşturup DOM'a ekler.
* Radio butonlarının "sadece tek bir tane seçilebilme" özelliğinin çalışması için üretilen tüm radio elemanlarını aynı gruba (`name` niteliği ile) dahil eder.
* Her yeni üretim talebinde, eski üretilen elemanları ekrandan temizler.

**Kullanılan Teknolojiler:**
* HTML
* CSS (Flexbox ile hizalama)
* Vanilla JavaScript (Saf JS)
