# smart_elevator_control_environment_reinforcement_learning
BLM5027 Derin Pekiştirmeli Öğrenme dersi finali YL

AKILLI ASANSÖR KONTROLÜ

Senaryo: Bir yapıda birden fazla asansör var. Yolcular yapının farklı katlarından asansör çağrıyor.

Amaç fonksiyonu: Bekleme süresini azaltmak, enerji tüketimini düşürmek ve verimli yolcu taşımak.

Durum(State): Katlarda bekleyen yolcuların sayısı, her asansörün mevcut katı, yönü(yukarı/ aşağı), yükü

Eylem(Action): Her asansör için bir sonraki hareket kararı(yukarı, aşağı, bekle, kapıyı aç)

Ödül(Reward): Yolcu taşıma +5, yolcunun zamanında asansöre binmesi +3, boşta gezinme -1, aynı katta iki asansör bekleme -5

İpucu: Asansör ajanları ayrı öğrenebilir (çok ajanlı öğrenme) veya merkezi bir ajan tüm sistemi kontrol edebilir.

Karışık sayıda katlarda bekleyen yolcu sayısı ve asansöre binen yolcu sayısı

Zamanı(t) minimize etmek

En az yol(x) 

![Adsız video ‐ Clipchamp ile yapıldı](https://github.com/user-attachments/assets/8d62fd0a-e9d2-4343-ba04-fbbf93efe334)

Şekil 1. Beş katlı bir binada tek asansörlü simülasyon ortamının genel görünümü.

Beş katlı bir binada iki asansörlü simülasyon ortamının genel görünümüne github reposundan ulaşabilirsiniz.


