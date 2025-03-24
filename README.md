Metro Ağı Simülasyonu

Proje Açıklaması

Bu proje, bir metro ağında iki istasyon arasındaki en hızlı ve en az aktarmalı rotayı bulan bir simülasyondur. BFS algoritması en az aktarmalı, A* algoritması ise en hızlı rotayı bulur. Metro ağı, istasyonlar ve bağlantılar ile bir graf yapısında modellenmiştir.

Kullanılan Teknolojiler

Python: Projenin temel programlama dili.

heapq: A* algoritması için öncelik kuyruğu uygulamak amacıyla kullanılmıştır.

collections: BFS algoritmasında kuyruk yapısı olarak deque veri yapısını kullanmak için kullanılmıştır.

Graph Veri Yapısı: Metro ağının modellemesi için düğümler (istasyonlar) ve kenarlar (bağlantılar) kullanılmıştır.

Algoritmaların Çalışma Mantığı

BFS (En Az Aktarmalı Rota)

BFS (Breadth-First Search) algoritması, genişlik öncelikli tarama yaparak en az hat değişikliği ile hedefe ulaşan en kısa rotayı bulur. İlk olarak başlangıç istasyonu kuyruk yapısına eklenir ve her adımda komşu istasyonlar ziyaret edilerek hedef istasyona ulaşana kadar genişletilir.

A* (En Hızlı Rota)

A* (A-Star) algoritması, en kısa yolu bulmak için kullanılan bir arama algoritmasıdır. Algoritma, her düğümü değerlendirirken toplam maliyet (şu ana kadar kat edilen süre + tahmini kalan süre) hesaplar ve en düşük maliyetli yolu takip eder. Metro ağında, en hızlı rotayı bulmak için süre bazlı bir öncelik kuyruğu kullanılmıştır.

Neden Bu Algoritmalar Kullanıldı?

BFS, en kısa yolun (düğüm sayısı bazında) bulunması için en ideal algoritmalardan biridir. Metro ağında en az aktarmalı rotayı belirlemek için uygundur.

A*, tahminsel maliyet yaklaşımı sayesinde süre bazlı en kısa yolu bulmada etkilidir. Gerçek dünya navigasyon sistemlerinde yaygın olarak kullanılır.

Geliştirme Fikirleri

Gerçek dünya metro hatlarının eklenmesi: İstanbul, Londra veya New York gibi şehirlerin gerçek metro hatları modele dahil edilebilir.

Grafiksel görselleştirme: Metro haritasının çizilmesi ve rotaların görsel olarak gösterilmesi sağlanabilir.

Dinamik trafik ve gecikme süreleri: Yoğun saatlerde gecikme süreleri eklenerek daha gerçekçi bir model oluşturulabilir.

Alternatif rota önerileri: Kullanıcının tercihlerine göre (örneğin daha az yürüme mesafesi veya daha az kalabalık hatlar) alternatif rotalar sunulabilir.
