![TryHackMe](https://assets.tryhackme.com/img/THMlogo.png)
# SimpleCTF Çözümü

CTF'imizi çözmeye başlayalım.

İlk olarak zafiyetli makinemizi tarayacağız. Terminalimizi açıyoruz. 

`nmap -A -Pn hedef_IP` komutumuzu çalıştırıyoruz. 
Burada nmap aracımız ağdaki açıkları tespit etmek için kullanılandığımız bir araçtır. 
`-A` parametresi ile işletim sistemi, sürüm algılama, komut dosyası tarama ve bir veri 
paketinin kaynaktan hedefe kadar izlediği yolu öğrenebiliriz.
`-Pn` parametresi hedef portlarda yapılan filtreleme ile portu kapalı gösterme olayını 
bypass ederek hedefin açık olduğunu varsayarak işlem yapmamızı sağlar.


