container vs AMI

container
AMI benzer ve imagelar ile calisir
3e ayrilir
- kendi ihtiyaclarimiza gore AMI dosyalari olusturma 
- docker tarafindan saglanan AMI`ler (nginx)
- comminuty`nin urettigi open source AMI`ler

docker AMi`lerinin saklandigi yapilara Registery denir 2 tanedir
- private Registery 
- public Registery (popular dockerHUB)

image 1
image 2
image 3

ilk container olusturuldu 

1-hello-world komutunu komutu ile sistemde olup olmadigina bakti ve sistemden cekti
2-AMI`den container olusturdu
3-icindeki uygulama calisti ekrana 3.png yazdirildi ve durdu
!! bir container sadece icerisinde calismasini istedigimiz ugulama calistigi surece calisir uygulama durursa yada kapatilirsa durur ya da kapanir

image 4 - komutu ile systemdeki containerlari listeler 

image 5 - pull islemi makinaya copyalar

image 6 -run islemleri
- nginx amisini bul bundan container yap sunucumun ismi websunucum olsun -d ile arkaplanda yani (deattach) olmasini sagladi portunu belirledik

image 7
image 8
image 9
image 10
image 11
image 12