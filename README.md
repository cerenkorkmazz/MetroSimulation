Metro Ağı Simülasyonu

Proje Açıklaması

Bu proje, metro ağında iki istasyon arasındaki en hızlı ve en az aktarmalı rotayı bulan bir simülasyondur. BFS algoritması en az aktarmalı, A* algoritması ise en hızlı rotayı bulur. Metro ağı, düğümler (istasyonlar) ve kenarlar (bağlantılar) kullanılarak modellenmiştir.

Kullanılan Teknolojiler

Python: Temel programlama dili.

heapq: A* algoritması için öncelik kuyruğu.

collections: BFS algoritmasinda deque yapısı.

Graph Veri Yapısı: Metro ağı modellemesi için kullanılmıştır.

Algoritmalar

BFS (En Az Aktarmalı Rota)

BFS, genişlik öncelikli arama yaparak en az aktarma ile hedefe ulaşan en kısa rotayı belirler. Algoritma, kuyruk yapısı kullanarak istasyonları katman katman ziyaret eder.

A* (En Hızlı Rota)

A*, toplam maliyet (geçilen süre + tahmini kalan süre) hesaplayarak en hizlı rotayı bulur. Öncelik kuyruğu ile çalişan bu algoritma, en kısa sürede hedefe ulaşmayı sağlar. 

Geliştirme Fikirleri

Gerçek metro hatları eklenebilir.

Görselleştirme eklenebilir.

Trafik ve gecikme süreleri dinamikleştirilebilir.

Alternatif rota seçenekleri sunulabilir.

Kullanıcı dostu bir arayüz eklenerek etkileşimli hale getirilebilir.

