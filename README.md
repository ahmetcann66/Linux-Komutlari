# Linux-Komutlari

# Sistem Yönetimi ve Bilgi Görüntüleme Komutları

## `df` Komutu
Bir dosya sisteminde yer alan toplam alana ve kullanılabilir alana ilişkin bilgileri görüntülemek için kullanılır.

```Bash
df
```

![isim](Images/df.png "çıklama")

## `df -a` Komutu
Dosya sisteminin tüm ayrıntılarını gösterir.

 ```Bash
df -a
```

![isim](Images/df%20-a.png "çıklama")

## `df -h` Komutu
Dosya sisteminin kullanım bilgilerini insan tarafından okunabilir formatta gösterir.
 ```Bash
df -h
```

![isim](Images/df%20-h.png "çıklama")

## `df -i` Komutu
Dosya sistemi inode kullanım bilgilerini gösterir.
 ```Bash
df -i
```

![isim](Images/df%20-i.png "çıklama")

## `top` Komutu
Çalışan işlemlerin ve çekirdek tarafından yönetilen görevlerin dinamik, gerçek zamanlı görünümünü gösterir.

```Bash
top
```

![isim](Images/top.png "çıklama")

## `top -d 5` Komutu
omutunu her 5 saniyede bir günceller.
```Bash
top -d 5
```

![isim](Images/top%20-d%205.png "çıklama")

## `top -n 10` Komutu
komutunun çıktısını 10 kez tekrarlar.
```Bash
top -n 10
```

![isim](Images/top%20-n%2010.png "çıklama")

## `top -p 1234` Komutu
Belirtilen işlem ID'sine (PID) sahip işlemi top komutuyla gösterir.
```Bash
top -p 1234
```

![isim](Images/top -p 1234.png "çıklama")

## `top -u username` Komutu
Belirli bir kullanıcının işlemlerini gösterir.
```Bash
top -u username
```

![isim](Images/top -u username.png "çıklama")

## `uptime` Komutu
 Sistemin ne kadar süre aktif kaldığını gösterir.

 ```Bash
uptime
```

![isim](Images/uptime.png "çıklama")

## `uname` Komutu
 Sistem hakkında bilgi verir. Geçerli makine ve üzerinde çalışdığı işletim sistemi hakkında isim, sürüm ve diğer ayrıntıları yazdırır.

```Bash
uname
```

![isim](Images/uname.png "çıklama")

## `neofetch` Komutu
Sisteminizin bilgilerini işletim sistemi logonuzun veya seçtiğiniz herhangi bir ASCII dosyasının hemen yanında görüntüleyen bir komut satırı aracıdır.

```Bash
neofetch
```

![isim](Images/neofetch.png "çıklama")

## `lscpu` Komutu
 Sistemdeki CPU'lar hakkında ayrıntılı bir bilgi listesi sağlar.

```Bash
lscpu
```

![isim](Images/lscpu.png "çıklama")

## `ifconfig` Komutu
Ağ arabirimi STRUCTURE yapısının dinamik olarak yaratılmasına ya da çekirdek belleğinden silinmesine olanak tanıyan ağ arabirimi yapılandırma aracıdır.

```Bash
ifconfig
```

![isim](Images/ifconfig.png "çıklama")

## `free` Komutu
Sisteminizdeki RAM belleğini kontrol etmenizi veya Linux işletim sisteminin bellek istatistiklerini kontrol etmenizi sağlar.

```Bash
free
```


![isim](Images/free.png "çıklama")

## `lshw` Komutu
Sistemin sahip olduğu donanımlarla ilgili ayrıntılı bilgi veren konsol programıdır.

```Bash
lshw
```

![isim](Images/lshw.png "çıklama")

## `history` Komutu
Komut geçmişi listesiyle çalışır.

```Bash
history
```

![isim](Images/history.png "çıklama")

## `dmesg` Komutu
Kernel mesajlarını gösterir.
 ```Bash
dmesg
```

![isim](Images/dmesg.png "çıklama")

## `dmesg | grep error` Komutu
dmesg çıktısındaki hataları filtreler.
 ```Bash
dmesg | grep error
```

![isim](Images/dmesg | grep error.png "çıklama")

## `lsof` Komutu
Açık dosyaları listeler.
 ```Bash
lsof
```

![isim](Images/lsof.png "çıklama")

## `ps` Komutu
Çalışan süreçleri gösterir.
 ```Bash
ps
```

![isim](Images/ps.png "çıklama")

## `vmstat ` Komutu
 Sistem durumu bilgilerini gösterir.
 ```Bash
vmstat 
```

![isim](Images/vmstat .png "çıklama")

## `sysctl -a` Komutu
Tüm çekirdek parametrelerini listeler.

 ```Bash
sysctl -a
```

![isim](Images/

## `systemctl` Komutu
Systemd hizmetlerini yönetir.
 ```Bash
systemctl
```

![isim](Images/systemctl.png "çıklama")

## `timedatectl` Komutu
Tarih ve saat yönetimi.
 ```Bash
timedatectl
```

![isim](Images/timedatectl.png "çıklama")

## `w` Komutu
 Sisteme giriş yapan kullanıcıları gösterir.
 ```Bash
w
```

![isim](Images/w.png "çıklama")

# Sistem Durumu ve Konfigürasyon


## `init ` Komutu
Sistemi farklı çalışma seviyelerine geçirir.
 ```Bash
init 
```

![isim](Images/init .png "çıklama")

## `vmstat ` Komutu
 Sistem durumu bilgilerini gösterir.
 ```Bash
vmstat 
```

![isim](Images/vmstat .png "çıklama")

## `last ` Komutu
Sistem oturumlarını listeler.
 ```Bash
last 
```

![isim](Images/last .png "çıklama")

## `less ` Komutu
Dosya içeriğini sayfa sayfa görüntüler.
 ```Bash
less 
```

![isim](Images/less .png "çıklama")

## `sudo ` Komutu
Yönetici haklarıyla komutla çalıştırır.
 ```Bash
sudo 
```

![isim](Images/sudo .png "çıklama")

## `sudo visudo` Komutu
sudokesintileri düzenler.
```Bash
sudo visudo
```

![isim](Images/sudo visudo.png "çıklama")

# yedekleme ve senkronizasyon


## `rsync` Komutu
Dosya saklamayı yapar.
```Bash
rsync
```

![isim](Images/rsync.png "çıklama")



# Kullanıcı ve Hesap Yönetimi

## `adduser` Komutu
Bir kullanıcı oluşturmak için kullanılan bir yardımcı programdır.

```Bash
adduser
```

![isim](Images/adduser.png "çıklama")

## `whomi` Komutu
Betiği hangi kullanıcının çalıştırdığını gösterir.

```Bash
whoami
```

![isim](Images/whoami.png "çıklama")

## `passwd` Komutu
Kullanıcı hesapları için parolaları değiştirir.

```Bash
passwd
```

![isim](Images/passwd.png "çıklama")

## `passwd -l` Komutu
Kullanıcı parolasını kilitler.
```Bash
passwd -l
```

![isim](Images/passwd -l.png "çıklama")


## `id` Komutu
Gerçek ya da etkin kimlik yerine oturum açma kimliğini yazdığını belirtir.

```Bash
id
```

![isim](Images/id.png "çıklama")

## `deluser` Komutu
Bir kullanıcıyı siler.
```Bash
deluser
```

![isim](Images/deluser.png "çıklama")

## `useradd` Komutu
 Yeni bir kullanıcı hesabı ekler.
```Bash
useradd
```

![isim](Images/useradd.png "çıklama")

## `useradd -m` Komutu
Yeni kullanıcı için ev dizini oluşturur.
```Bash
useradd -m
```

![isim](Images/useradd -m.png "çıklama")

## `useradd -s` Komutu
Kullanıcı için shell belirtir.
```Bash
useradd -s
```

![isim](Images/useradd -s.png "çıklama")

## `chage` Komutu
Kullanıcı parolasının süresini ayarlamak için kullanılır.
```Bash
chage
```

![isim](Images/chage.png "çıklama")

## `groupadd` Komutu
Yeni bir kullanıcı grubu oluşturur.
```Bash
groupadd
```

![isim](Images/groupadd.png "çıklama")

## `groupdel` Komutu
Bir kullanıcı grubunu siler.
```Bash
groupdel
```

![isim](Images/groupdel.png "çıklama")

## `groups` Komutu
Kullanıcının dahil olduğu grupları gösterir.
```Bash
groups
```

![isim](Images/groups.png "çıklama")



# Dosya ve Dizin Yönetimi

## `ls` Komutu
İlgili dizide(klasörde) ki diğer erişilebilir dizileri gösteriyor.

```Bash
ls
```

![isim](Images/ls.png "ls Komutu")

## `ls -a` Komutu
Bir dizinin içeriğini ek ayrıntılarla birlikte(gizli dosyalar dahil) bir liste olarak görüntülemek için kullanılır.

```Bash
ls -a
```

![isim](Images/ls_a.png "çıklama")

## `pwd` Komutu
Mevcut dizinin yolunu yazdıran bir komuttur.

```Bash
pwd
```

![isim](Images/pwd.png "çıklama")

## `touch` Komutu
ir bilgisayar dosyasının veya dizininin son kullanım ve/veya düzenlenme tarihini güncellemek için kullanılan bir komuttur.

```Bash
touch
```

![isim](Images/touch.png "çıklama")

## `clear` Komutu
Yazılan komutları ekranı temizler.

```Bash
clear
```
![isim](Images/clear.png "çıklama")

## `ls -a` Komutu
Bir dizinin içeriğini ek ayrıntılarla birlikte(gizli dosyalar dahil) bir liste olarak görüntülemek için kullanılır.

```Bash
ls -a
```

![isim](Images/ls_a.png "çıklama")

## `cd ..` Komutu
Bir üst dizine geçer.
```Bash
cd ..
```

![isim](Images/cd ...png "çıklama")

## `ln` Komutu
Dosya için bağlantı oluşturur
```Bash
ln
```

![isim](Images/ln.png "çıklama")

## `ln -s` Komutu
Sembolik bağlantı oluşturur.
```Bash
ln -s
```

![isim](Images/ln -s.png "çıklama")

## `ls -l` Komutu
Dosya ve dizinleri uzun formatta listeler.
```Bash
ls -l
```

![isim](Images/ls -l.png "çıklama")

## `mkdir` Komutu
Yeni bir dizin oluşturur.
```Bash
mkdir
```

![isim](Images/mkdir.png "çıklama")

## `mv` Komutu
Dosya veya dizin taşır veya yeniden adlandırır.
```Bash
mv
```

![isim](Images/mv.png "çıklama")

## `rm` Komutu
Dosya veya dizin siler.
```Bash
rm
```

![isim](Images/rm.png "çıklama")

## `find` Komutu
Dosya aramak için kullanılır.
```Bash
find
```

![isim](Images/find.png "çıklama")

## `file` Komutu
Dosyanın türünü gösterir.
```Bash
file
```

![isim](Images/file.png "çıklama")

## `stat` Komutu
Dosyanın veya dizinin stat bilgilerini gösterir.
```Bash
stat
```

![isim](Images/stat.png "çıklama")

## `du` Komutu
Dizin ve dosyaların disk kullanımını gösterir.
```Bash
du
```

![isim](Images/du.png "çıklama")

## `lsusb` Komutu
USB aygıtlarını listeler.
```Bash
lsusb
```

![isim](Images/lsusb.png "çıklama")

## `lsusb -v` Komutu
USB aygıtlarının ayrıntılı bilgisini gösterir.
```Bash
lsusb -v```

![isim](Images/lsusb -v.png "çıklama")

# Sistem Kapama ve Yeniden Başlatma

## `poweroff` Komutu
Sistemi kapatır.
```Bash
poweroff
```

![isim](Images/poweroff.png "çıklama")

## `shut` Komutu
Bilgisayarın sağlıklı bir şekilde kapanmasını sağlar.

```Bash
shut
```

![isim](Images/shut.png "çıklama")

## `halt` Komutu
Sistemi hemen kapatır.
```Bash
halt
```

![isim](Images/halt.png "çıklama")

## `reboot` Komutu
Sistemi yeniden başlatır.
```Bash
reboot
```

![isim](Images/reboot.png "çıklama")

# Ağ ve İletişim

## `echo` Komutu
Karakter dizgilerini standart çıkışa yazar.

```Bash
echo
```

![isim](Images/echo.png "çıklama")

## `date` Komutu
İşaret olmadan ya da + (artı işareti) ile başlayan bir işaret listesiyle çağrılırsa, geçerli tarih ve saati standart çıkışa yazar.

```Bash
date
```

![isim](Images/date.png "çıklama")

## `aprops ls` Komutu
Belirtilen dize veya dizeleri ( anahtar sözcükler olarak adlandırılır) tüm kılavuz sayfalarının "ad" bölümlerinde aramak için kullanılır.

```Bash
aprops ls
```

![isim](Images/apropos.png "çıklama")



## `wget` Komutu
Dosya indirmek için kullanılır.
```Bash
wget
```

![isim](Images/wget.png "çıklama")

## `curl` Komutu
Verileri almak veya göndermek için kullanılır.
```Bash
curl
```

![isim](Images/curl.png "çıklama")

## `hostname` Komutu
Sistemin hostname'ini gösterir.
```Bash
hostname
```

![isim](Images/hostname.png "çıklama")

## `route` Komutu
Yönlendirme tablosunu gösterir.
```Bash
route
```

![isim](Images/route.png "çıklama")

## `dig` Komutu
DNS sorguları yapar.
```Bash
dig
```

![isim](Images/dig.png "çıklama")

## `nslookup` Komutu
İşaret olmadan ya da + (artı işareti) ile başlayan bir işaret listesiyle çağrılırsa, geçerli tarih ve saati standart çıkışa yazar.

```Bash
nslookup
```

![isim](Images/nslookup.png "çıklama")

## `ss -tuln` Komutu
Dinleyen soket bağlantılarını gösterir.
```Bash
ss -tuln
```

![isim](Images/ss -tuln.png "çıklama")

## `ss` Komutu
 Soket bağlantılarını gösterir.
```Bash
ss
```

![isim](Images/ss.png "çıklama")

## `netstat -tuln` Komutu
Dinleyen ağ bağlantılarını gösterir.
```Bash
netstat -tuln
```

![isim](Images/netstat -tuln.png "çıklama")

## `netstat -rn` Komutu
Yönlendirme tablosunu gösterir
```Bash
netstat -rn
```

![isim](Images/netstat -rn.png "çıklama")

## `netstat -an` Komutu
Ağ bağlantılarını ve portları listeler.
```Bash
netstat -an
```

![isim](Images/netstat -an.png "çıklama")

## `netstat` Komutu
Ağ bağlantılarının listesini gösterir.
```Bash
netstat
```

![isim](Images/netstat.png "çıklama")

## `scp` Komutu
Güvenli dosya kopyalama komutu.
```Bash
scp
```

![isim](Images/scp.png "çıklama")

## `ssh` Komutu
Dosya indirmek için kullanılır.
```Bash
ssh
```

![isim](Images/ssh.png "çıklama")

## `scp` Komutu
Güvenli dosya kopyalama komutu.
```Bash
scp
```

![isim](Images/scp.png "çıklama")

# Diğer Kullanışlı Komutlar


## `!!` Komutu
En son çalıştırılan komutu tekrar çalıştırır.

```Bash
!!
```

![isim](Images/!!.png "çıklama")


## `fdisk` Komutu
Sabit diskte bölümler oluşturmak, silmek, yeniden boyutlandırmak, değiştirmek ve taşımak için kullanılır.

```Bash
fdisk
```

![isim](Images/fdisk.png "çıklama")

## `alias` Komutu
Komutlara kısaltmalar tanımlar.

```Bash
alias
```

![isim](Images/alias.png "çıklama")

## `sed` Komutu
Akış düzenleyicisi, metin üzerinde işlemler yapar.

```Bash
sed
```

![isim](Images/sed.png "çıklama")

## `awk` Komutu
Metin işleme ve veri analizi aracı.

```Bash
awk
```

![isim](Images/awk.png "çıklama")

## `watch` Komutu
Komutları belirli aralıklarla tekrar eder.

```Bash
watch
```

![isim](Images/watch.png "çıklama")

## `zip` Komutu
Dosya sıkıştırma komutudur.

```Bash
zip
```

![isim](Images/zip.png "çıklama")

## `stat` Komutu
Dosyanın ya da dizinin durumunu gösterir.

```Bash
stat
```

![isim](Images/stat.png "çıklama")



