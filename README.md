THANK YOU CLAUDE
zabbix 7.4 cambium template 
3. Numerik OID'lere çevir (kalıcı/önerilen çözüm — yaptım): Şablondaki tüm CAMBIUM-PTP650-MIB::..., IF-MIB::... ve DISMAN-EVENT-MIB::sysUpTimeInstance OID'lerini, Cambium'ın resmi MIB tanımındaki (enterprises.17713.7...) gerçek numerik karşılıklarıyla değiştirdim. Numerik OID kullanınca server'ın MIB dosyasına ihtiyacı kalmıyor, bu hata tamamen ortadan kalkıyor.
4. 
Zabbix 7.4'e Configuration → Templates → Import ile yükleyebilirsin (mevcut adı aynı, "Update existing" ile üzerine yazabilir veya yeni template olarak alıp host'a bağlayabilirsin).
