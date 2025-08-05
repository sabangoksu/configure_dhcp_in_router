
# Cisco Router Üzerinden DHCP Yapılandırma Çalışması

Bu çalışmada Cisco router üzerinden DHCP protokolünün nasıl yapılandırıldığını öğrendim. Aşağıdaki konulara özellikle odaklandım:

- `hostname` komutu ile router’a isim vermeyi,  
- Arayüzlere (`FastEthernet0/0`, `FastEthernet0/1`) IP adresi atamayı ve arayüzleri aktif hale getirmeyi,   
- `ip dhcp excluded-address` komutu ile belirli IP adreslerini DHCP havuzunun dışında bırakmayı,  
- `ip dhcp pool` komutu ile DHCP havuzu oluşturmayı,  
- `default-router` ve `dns-server` komutları ile istemcilere ağ geçidi ve DNS bilgilerini otomatik olarak atamayı,  
- Yapılandırma sonrası `show ip interface brief` komutu ile arayüz durumlarını kontrol etmeyi,  


Bu yapılandırmayı hem teorik olarak hem de simülasyon ortamında (örneğin Cisco Packet Tracer) test ederek uygulamalı şekilde öğrenmiş oldum.
