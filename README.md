# Linux-Komutlari 👨‍💻👩‍💻
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Linux Mint](https://img.shields.io/badge/Linux%20Mint-87CF3E?style=for-the-badge&logo=Linux%20Mint&logoColor=white)

## Açıklama

Bu repo, Linux işletim sisteminde sıkça kullanılan komutları ve bu komutların kullanım örneklerini içermektedir. Her komut için açıklamalar, kullanım örnekleri ve çıktı görselleri bulunmaktadır. Bu kaynak, Linux kullanıcıları için bir referans kılavuzu olarak hazırlanmıştır ve şu kategorileri içermektedir:


## İçindekiler 🗒️
| Bölüm | Alt Başlıklar |
|-------|---------------|
| [Sistem Yönetimi ve Bilgi Görüntüleme Komutları](#sistem-yönetimi-ve-bilgi-görüntüleme-komutları-) | df, top, uptime, uname, neofetch, lscpu, ifconfig, free, lshw, history, dmesg, lsof, ps, vmstat, sysctl, systemctl, timedatectl, w |
| [Sistem Durumu ve Konfigürasyon](#sistem-durumu-ve-konfigürasyon) | init, vmstat, last, less, sudo |
| [Yedekleme ve Senkronizasyon](#yedekleme-ve-senkronizasyon) | rsync |
| [Kullanıcı ve Hesap Yönetimi](#kullanıcı-ve-hesap-yönetimi) | adduser, whoami, passwd, id, deluser, useradd, chage, groupadd, groupdel, groups |
| [Dosya ve Dizin Yönetimi](#dosya-ve-dizin-yönetimi) | ls, pwd, touch, clear, cd, ln, mkdir, mv, rm, find, file, stat, du, lsusb |
| [Sistem Kapatma ve Yeniden Başlatma](#sistem-kapatma-ve-yeniden-başlatma) | poweroff, shut, halt, reboot |
| [Ağ ve İletişim](#ağ-ve-iletişim) | echo, date, apropos, wget, curl, hostname, route, dig, nslookup, ss, netstat, ssh, scp |
| [Diğer Kullanışlı Komutlar](#diğer-kullanışlı-komutlar) | !!, fdisk, alias, sed, awk, watch, zip, stat |

# Sistem Yönetimi ve Bilgi Görüntüleme Komutları 🖥️

## `df` Komutu
Bir dosya sisteminde yer alan toplam alana ve kullanılabilir alana ilişkin bilgileri görüntülemek için kullanılır.

```Bash
df
```

![isim](Imagess/df.png "çıklama")

## `df -a` Komutu
Dosya sisteminin tüm ayrıntılarını gösterir.

 ```Bash
df -a
```

![isim](Imagess/df%20-a.png "çıklama")

## `df -h` Komutu
Dosya sisteminin kullanım bilgilerini insan tarafından okunabilir formatta gösterir.
 ```Bash
df -h
```

![isim](Imagess/df%20-h.png "çıklama")

## `df -i` Komutu
Dosya sistemi inode kullanım bilgilerini gösterir.
 ```Bash
df -i
```

![isim](Imagess/df%20-i.png "çıklama")

## `top` Komutu
Çalışan işlemlerin ve çekirdek tarafından yönetilen görevlerin dinamik, gerçek zamanlı görünümünü gösterir.

```Bash
top
```

![isim](Imagess/top.png "çıklama")

## `top -d 5` Komutu
omutunu her 5 saniyede bir günceller.
```Bash
top -d 5
```

![isim](Imagess/top%20-d%205.png "çıklama")

## `top -n 10` Komutu
komutunun çıktısını 10 kez tekrarlar.
```Bash
top -n 10
```

![isim](Imagess/top%20-n%2010.png "çıklama")

## `top -p 1234` Komutu
Belirtilen işlem ID'sine (PID) sahip işlemi top komutuyla gösterir.
```Bash
top -p 1234
```

![isim](Imagess/top%20-p%201234.png "çıklama")

## `top -u username` Komutu
Belirli bir kullanıcının işlemlerini gösterir.
```Bash
top -u username
```

![isim](Imagess/top%20-u%20username.png "çıklama")

## `uptime` Komutu
 Sistemin ne kadar süre aktif kaldığını gösterir.

 ```Bash
uptime
```

![isim](Imagess/uptime.png "çıklama")

## `uname` Komutu
 Sistem hakkında bilgi verir. Geçerli makine ve üzerinde çalışdığı işletim sistemi hakkında isim, sürüm ve diğer ayrıntıları yazdırır.

```Bash
uname
```

![isim](Imagess/uname.png "çıklama")

## `neofetch` Komutu
Sisteminizin bilgilerini işletim sistemi logonuzun veya seçtiğiniz herhangi bir ASCII dosyasının hemen yanında görüntüleyen bir komut satırı aracıdır.

```Bash
neofetch
```

![isim](Imagess/neofetch.png "çıklama")

## `lscpu` Komutu
 Sistemdeki CPU'lar hakkında ayrıntılı bir bilgi listesi sağlar.

```Bash
lscpu
```

![isim](Imagess/lscpu.png "çıklama")

## `ifconfig` Komutu
Ağ arabirimi STRUCTURE yapısının dinamik olarak yaratılmasına ya da çekirdek belleğinden silinmesine olanak tanıyan ağ arabirimi yapılandırma aracıdır.

```Bash
ifconfig
```

![isim](Imagess/ifconfig.png "çıklama")

## `free` Komutu
Sisteminizdeki RAM belleğini kontrol etmenizi veya Linux işletim sisteminin bellek istatistiklerini kontrol etmenizi sağlar.

```Bash
free
```


![isim](Imagess/free.png "çıklama")

## `lshw` Komutu
Sistemin sahip olduğu donanımlarla ilgili ayrıntılı bilgi veren konsol programıdır.

```Bash
lshw
```

![isim](Imagess/lshw.png "çıklama")

## `history` Komutu
Komut geçmişi listesiyle çalışır.

```Bash
history
```

![isim](Imagess/history.png "çıklama")

## `dmesg` Komutu
Kernel mesajlarını gösterir.
 ```Bash
dmesg
```

![isim](Imagess/dmesg.png "çıklama")

## `dmesg | grep error` Komutu
dmesg çıktısındaki hataları filtreler.
 ```Bash
dmesg | grep error
```

![isim](Imagess/dmesg%20_%20grep%20error.png "çıklama")

## `lsof` Komutu
Açık dosyaları listeler.
 ```Bash
lsof
```

![isim](Imagess/lsof.png "çıklama")

## `ps` Komutu
Çalışan süreçleri gösterir.
 ```Bash
ps
```

![isim](Imagess/ps.png "çıklama")

## `vmstat ` Komutu
 Sistem durumu bilgilerini gösterir.
 ```Bash
vmstat 
```

![isim](Imagess/vmstat.png "çıklama")

## `sysctl -a` Komutu
Tüm çekirdek parametrelerini listeler.

 ```Bash
sysctl -a
```

![isim](Imagess/sysctl%20-a.png "çıklama")

## `systemctl` Komutu
Systemd hizmetlerini yönetir.
 ```Bash
systemctl
```

![isim](Imagess/systemctl.png "çıklama")

## `timedatectl` Komutu
Tarih ve saat yönetimi.
 ```Bash
timedatectl
```

![isim](Imagess/timedatectl.png "çıklama")

## `w` Komutu
 Sisteme giriş yapan kullanıcıları gösterir.
 ```Bash
w
```

![isim](Imagess/w.png "çıklama")

# Sistem Durumu ve Konfigürasyon 👨‍💻


## `init ` Komutu
Sistemi farklı çalışma seviyelerine geçirir.
 ```Bash
init 
```

![isim](Imagess/init.png "çıklama")

## `vmstat ` Komutu
 Sistem durumu bilgilerini gösterir.
 ```Bash
vmstat 
```

![isim](Imagess/vmstat.png "çıklama")

## `last ` Komutu
Sistem oturumlarını listeler.
 ```Bash
last 
```

![isim](Imagess/last.png "çıklama")

## `less ` Komutu
Dosya içeriğini sayfa sayfa görüntüler.
 ```Bash
less 
```

![isim](Imagess/less%20xxx.png "çıklama")

## `sudo ` Komutu
Yönetici haklarıyla komutla çalıştırır.
 ```Bash
sudo 
```

![isim](Imagess/sudo.png "çıklama")

## `sudo visudo` Komutu
sudokesintileri düzenler.
```Bash
sudo visudo
```

![isim](Imagess/sudo%20visudo.png "çıklama")

# yedekleme ve senkronizasyon 🕖


## `rsync` Komutu
Dosya saklamayı yapar.
```Bash
rsync
```

![isim](Imagess/rsync.png "çıklama")



# Kullanıcı ve Hesap Yönetimi 👤

## `adduser` Komutu
Bir kullanıcı oluşturmak için kullanılan bir yardımcı programdır.

```Bash
adduser
```

![isim](Imagess/adduser.png "çıklama")

## `whomi` Komutu
Betiği hangi kullanıcının çalıştırdığını gösterir.

```Bash
whoami
```

![isim](Imagess/whoami.png "çıklama")

## `passwd` Komutu
Kullanıcı hesapları için parolaları değiştirir.

```Bash
passwd
```

![isim](Imagess/passwd.png "çıklama")

## `passwd -l` Komutu
Kullanıcı parolasını kilitler.
```Bash
passwd -l
```

![isim](Imagess/passwd%20-l.png "çıklama")


## `id` Komutu
Gerçek ya da etkin kimlik yerine oturum açma kimliğini yazdığını belirtir.

```Bash
id
```

![isim](Imagess/id.png "çıklama")

## `deluser` Komutu 
Bir kullanıcıyı siler.
```Bash
deluser
```

![isim](Imagess/deluser.png "çıklama")

## `useradd` Komutu
 Yeni bir kullanıcı hesabı ekler.
```Bash
useradd
```

![isim](Imagess/useradd.png "çıklama")

## `useradd -m` Komutu
Yeni kullanıcı için ev dizini oluşturur.
```Bash
useradd -m
```

![isim](Imagess/useradd%20-m.png "çıklama")

## `useradd -s` Komutu
Kullanıcı için shell belirtir.
```Bash
useradd -s
```

![isim](Imagess/useradd%20-s.png "çıklama")

## `chage` Komutu
Kullanıcı parolasının süresini ayarlamak için kullanılır.
```Bash
chage
```

![isim](Imagess/chage.png "çıklama")

## `groupadd` Komutu
Yeni bir kullanıcı grubu oluşturur.
```Bash
groupadd
```

![isim](Imagess/groupadd.png "çıklama")

## `groupdel` Komutu
Bir kullanıcı grubunu siler.
```Bash
groupdel
```

![isim](Imagess/groupdel.png "çıklama")

## `groups` Komutu
Kullanıcının dahil olduğu grupları gösterir.
```Bash
groups
```

![isim](Imagess/groups.png "çıklama")



# Dosya ve Dizin Yönetimi 🗂️

## `ls` Komutu
İlgili dizide(klasörde) ki diğer erişilebilir dizileri gösteriyor.

```Bash
ls
```

![isim](Imagess/ls.png "ls Komutu")

## `ls -a` Komutu
Bir dizinin içeriğini ek ayrıntılarla birlikte(gizli dosyalar dahil) bir liste olarak görüntülemek için kullanılır.

```Bash
ls -a
```

![isim](Imagess/ls_a.png "çıklama")

## `pwd` Komutu
Mevcut dizinin yolunu yazdıran bir komuttur.

```Bash
pwd
```

![isim](Imagess/pwd.png "çıklama")

## `touch` Komutu
ir bilgisayar dosyasının veya dizininin son kullanım ve/veya düzenlenme tarihini güncellemek için kullanılan bir komuttur.

```Bash
touch
```

![isim](Imagess/touch.png "çıklama")

## `clear` Komutu
Yazılan komutları ekranı temizler.

```Bash
clear
```
![isim](Imagess/clear.png "çıklama")

## `ls -a` Komutu
Bir dizinin içeriğini ek ayrıntılarla birlikte(gizli dosyalar dahil) bir liste olarak görüntülemek için kullanılır.

```Bash
ls -a
```

![isim](Imagess/ls_a.png "çıklama")

## `cd ..` Komutu
Bir üst dizine geçer.
```Bash
cd ..
```

![isim](Imagess/cd%20...png "çıklama")

## `ln` Komutu
Dosya için bağlantı oluşturur
```Bash
ln
```

![isim](Imagess/ln.png "çıklama")

## `ln -s` Komutu
Sembolik bağlantı oluşturur.
```Bash
ln -s
```

![isim](Imagess/ln%20-s.png "çıklama")

## `ls -l` Komutu
Dosya ve dizinleri uzun formatta listeler.
```Bash
ls -l
```

![isim](Imagess/ls%20-l.png "çıklama")

## `mkdir` Komutu
Yeni bir dizin oluşturur.
```Bash
mkdir
```

![isim](Imagess/mkdir.png "çıklama")

## `mv` Komutu
Dosya veya dizin taşır veya yeniden adlandırır.
```Bash
mv
```

![isim](Imagess/mv%20xxx.png "çıklama")

## `rm` Komutu
Dosya veya dizin siler.
```Bash
rm
```

![isim](Imagess/rm%20xxx.png "çıklama")

## `find` Komutu
Dosya aramak için kullanılır.
```Bash
find
```

![isim](Imagess/find.png "çıklama")

## `file` Komutu
Dosyanın türünü gösterir.
```Bash
file
```

![isim](Imagess/file.png "çıklama")

## `stat` Komutu
Dosyanın veya dizinin stat bilgilerini gösterir.
```Bash
stat
```

![isim](Imagess/stat.png "çıklama")

## `du` Komutu
Dizin ve dosyaların disk kullanımını gösterir.
```Bash
du
```

![isim](Imagess/du.png "çıklama")

## `lsusb` Komutu
USB aygıtlarını listeler.
```Bash
lsusb
```

![isim](Imagess/lsusb.png "çıklama")

## `lsusb -v` Komutu
USB aygıtlarının ayrıntılı bilgisini gösterir.
```Bash
lsusb -v
```

![isim](Imagess/lsusb%20-v.png "çıklama")

Sistemi kapatır.

```Bash
poweroff
```

![isim](Imagess/poweroff.png "çıklama")

## `shut` Komutu
Bilgisayarın sağlıklı bir şekilde kapanmasını sağlar.

```Bash
shut
```

![isim](Imagess/shut.png"çıklama")

## `halt` Komutu
Sistemi hemen kapatır.
```Bash
halt
```

![isim](Imagess/halt.png "çıklama")

## `reboot` Komutu
Sistemi yeniden başlatır.
```Bash
reboot
```

![isim](Imagess/reboot.png "çıklama")

# Ağ ve İletişim 🛜

## `echo` Komutu
Karakter dizgilerini standart çıkışa yazar.

```Bash
echo
```

![isim](Imagess/echo.png "çıklama")

## `date` Komutu
İşaret olmadan ya da + (artı işareti) ile başlayan bir işaret listesiyle çağrılırsa, geçerli tarih ve saati standart çıkışa yazar.

```Bash
date
```

![isim](Imagess/date.png "çıklama")

## `aprops ls` Komutu
Belirtilen dize veya dizeleri ( anahtar sözcükler olarak adlandırılır) tüm kılavuz sayfalarının "ad" bölümlerinde aramak için kullanılır.

```Bash
aprops ls
```

![isim](Imagess/apropos.png "çıklama")



## `wget` Komutu
Dosya indirmek için kullanılır.
```Bash
wget
```

![isim](Imagess/wget.png "çıklama")

## `curl` Komutu
Verileri almak veya göndermek için kullanılır.
```Bash
curl
```

![isim](Imagess/curl.png "çıklama")

## `hostname` Komutu
Sistemin hostname'ini gösterir.
```Bash
hostname
```

![isim](Imagess/hostname.png "çıklama")

## `route` Komutu
Yönlendirme tablosunu gösterir.
```Bash
route
```

![isim](Imagess/route.png "çıklama")

## `dig` Komutu
DNS sorguları yapar.
```Bash
dig
```

![isim](Imagess/dig.png "çıklama")

## `nslookup` Komutu
İşaret olmadan ya da + (artı işareti) ile başlayan bir işaret listesiyle çağrılırsa, geçerli tarih ve saati standart çıkışa yazar.

```Bash
nslookup
```

![isim](Imagess/nslookup.png "çıklama")

## `ss -tuln` Komutu
Dinleyen soket bağlantılarını gösterir.
```Bash
ss -tuln
```

![isim](Imagess/ss%20-tuln.png "çıklama")

## `ss` Komutu
 Soket bağlantılarını gösterir.
```Bash
ss
```

![isim](Imagess/ss.png "çıklama")

## `netstat -tuln` Komutu
Dinleyen ağ bağlantılarını gösterir.
```Bash
netstat -tuln
```

![isim](Imagess/netstat%20-tuln.png "çıklama")

## `netstat -rn` Komutu
Yönlendirme tablosunu gösterir
```Bash
netstat -rn
```

![isim](Imagess/netstat%20-rn.png "çıklama")

## `netstat -an` Komutu
Ağ bağlantılarını ve portları listeler.
```Bash
netstat -an
```

![isim](Imagess/netstat%20-an.png "çıklama")

## `netstat` Komutu
Ağ bağlantılarının listesini gösterir.
```Bash
netstat
```

![isim](Imagess/netstat.png "çıklama")


## `ssh` Komutu
Dosya indirmek için kullanılır.
```Bash
ssh
```

![isim](Imagess/ssh.png "çıklama")

## `scp` Komutu
Güvenli dosya kopyalama komutu.
```Bash
scp
```

![isim](Imagess/scp.png "çıklama")

# Diğer Kullanışlı Komutlar ♟️


## `!!` Komutu
En son çalıştırılan komutu tekrar çalıştırır.

```Bash
!!
```

![isim](Imagess/!!.png "çıklama")


## `fdisk` Komutu
Sabit diskte bölümler oluşturmak, silmek, yeniden boyutlandırmak, değiştirmek ve taşımak için kullanılır.

```Bash
fdisk
```

![isim](Imagess/fdisk.png "çıklama")

## `alias` Komutu
Komutlara kısaltmalar tanımlar.

```Bash
alias
```

![isim](Imagess/alias.png "çıklama")

## `sed` Komutu
Akış düzenleyicisi, metin üzerinde işlemler yapar.

```Bash
sed
```

![isim](Imagess/sed.png "çıklama")

## `awk` Komutu
Metin işleme ve veri analizi aracı.

```Bash
awk
```

![isim](Imagess/awk.png "çıklama")

## `watch` Komutu
Komutları belirli aralıklarla tekrar eder.

```Bash
watch
```

![isim](Imagess/watch%20-n%201%20df%20-h.png "çıklama")

## `zip` Komutu
Dosya sıkıştırma komutudur.

```Bash
zip
```

![isim](Imagess/zip.png "çıklama")

## `stat` Komutu
Dosyanın ya da dizinin durumunu gösterir.

```Bash
stat
```

![isim](Imagess/stat.png "çıklama")

## Kaynakça 📨

1. Linux man pages. (t.y.). die.net. https://linux.die.net/man/


## Uyarı ‼️
Bazı komutlar sisteminiz üzerinde değişiklikler yaparak veri kaybına neden olabilir.Lütfen komutları kullanırken ne işe yaradıklarına dikkat edin !!

## İletişim 📞
ahmetcanbozkurt295@gmail.com



