# Bounty Hacker

![TryHackMeLogo](https://github.com/cdemir7/TryHackMe-CTF-Solutions/blob/main/Basic-Pentesting/Basic-Pentesting-Images/TryHackMeLogo.png)

Vpn i çalıştırıp odaya katılıyoruz.

Makineyi Çalıştıryoruz.

Daha sonra nmap ile tarama yapıyoruz.

![Bounty-Hacker-1](https://github.com/cdemir7/TryHackMe-CTF-Solutions/blob/main/Bounty-Hacker/Bounty-Hacker-Images/Bounty-Hacker-1.png)

Ftp portundan giriş yapalım.

Şimdi de ls komutu ile sistemde bulunan dosyaları listeliyoruz.

![Bounty-Hacker-2](https://github.com/cdemir7/TryHackMe-CTF-Solutions/blob/main/Bounty-Hacker/Bounty-Hacker-Images/Bounty-Hacker-2.png)

Dosyalarımızı bilgisayara indiriyoruz.

![Bounty-Hacker-3](https://github.com/cdemir7/TryHackMe-CTF-Solutions/blob/main/Bounty-Hacker/Bounty-Hacker-Images/Bounty-Hacker-3.png)

Dosyalarımızın içini listeliyoruz.

![Bounty-Hacker-4](https://github.com/cdemir7/TryHackMe-CTF-Solutions/blob/main/Bounty-Hacker/Bounty-Hacker-Images/Bounty-Hacker-4.png)

task.txt dosyamızın içinde yazarın adı yazıyor(lin).

locks.txt dosyamız ile de ssh portuna Hydra ile bir brute force saldırısı yapıyoruz.

![Bounty-Hacker-5](https://github.com/cdemir7/TryHackMe-CTF-Solutions/blob/main/Bounty-Hacker/Bounty-Hacker-Images/Bounty-Hacker-5.png)

Şifreyi bulduk.

Burada 4. sorumuzun cevabı da ssh oluyor.

5.sorunun cevabı: RedDr4gonSynd1cat3

Şimdi parolayıda bulduğumuza göre ssh portuna bağlanarak makineye erişim sağlıyoruz ve dosylarımızı listeliyoruz.

![Bounty-Hacker-6](https://github.com/cdemir7/TryHackMe-CTF-Solutions/blob/main/Bounty-Hacker/Bounty-Hacker-Images/Bounty-Hacker-6.png)

user.txt dosyasının içini cat ile görüntülüyoruz.

6.sorunun cevabı : THM{CR1M3_SyNd1C4T3}

sudo -l komutunu çalıştırarak root olmadan kullanabileceğimiz bir açık varsa listeliyoruz.

tar dizininde komut çalıştırabiliriz.
tar gtfobins yazarak araştırma yapıyoruz.
Bulduğumuz kodu çalıştırarak root yetkisini alıyoruz ve dosyamızı listeliyoruz.

![Bounty-Hacker-7](https://github.com/cdemir7/TryHackMe-CTF-Solutions/blob/main/Bounty-Hacker/Bounty-Hacker-Images/Bounty-Hacker-7.png)

Son sorunun cevabı : THM{80UN7Y_h4cK3r}
