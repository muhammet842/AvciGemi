# AvciGemi
Arduino ve ESP8266 tabanlı, GSM/VPN üzerinden uzaktan kontrol edilebilen, su kalitesi analizi (TDS/Sıcaklık) yapabilen İnsansız Deniz Aracı (İDA) prototipi.
Bu proje, çevre kirliliği ölçümü ve otonom/manuel kontrol yeteneklerine sahip bir İnsansız Deniz Aracı (İDA) çalışmasıdır.

Teknik Özellikler
Kontrol Ünitesi: Arduino Mega & ESP8266.

Haberleşme: SIM808 GSM Modülü ve VPN protokolleri ile mesafe sınırı olmaksızın kontrol.

Sensörler: TDS (Su Kalitesi) Sensörü, DS18B20 Sıcaklık Sensörü, DHT11 Sıcaklık ve Nem Sensörü, MQ-9 Gaz Sensörü, 9 Eksenli IMU Manyetik Alan Sensörü.

Yazılım: C++ (Embedded), HTML/CSS/JS (Kontrol Arayüzü).

Neyi Çözdüm?
Projenin geliştirme sürecinde karşılaştığım en büyük engel olan mesafe sınırı ve veri aktarımı sorununu; standart RF kumandalar yerine VPN tabanlı bir ağ mimarisi kurgulayarak çözdüm. Bu sayede aracın verilerini her yerden anlık olarak takip edebiliyoruz.
