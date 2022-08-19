# Techcareer Networ Security Bootcamp
![image](https://user-images.githubusercontent.com/48979284/185521637-5ef47f6b-67f1-45b4-8d3f-e0279e206482.png)

# İstenilenler

`Proje 1 : IPv4 omurga ve IPv6 omurga kendi içlerinde statik routing ile haberleşelebilmeli.`

`Proje 2 : IPv4 omurga ve IPv6 omurga kendi içlerinde ospf ile haberleşelebilmeli.`

`Her iki senaryo içinde İstanbul lokasyonunda gerekli L2 düzenlemeler sağlanmalı.`

`Serverlara sadece izin verilen portlardan ulaşılmalı.`

## İki projede ortak yapılanlar

*Topoloji tekrar çizildi.

*End Device'ların IP, GW ve DNS ayarlarını yapıldı.

*Router ve Switchlere temel ayarları yapıldı, hostnameler düzenlendi ve password verildi.

1.Proje için `password cisco` `secret tech`

2.Proje için `password cisco` `secret ciscoo`
olarak ayarlanmıştır.

*Switchlerdeki erişime izin verilen portların dışındaki portlar kapatıldı.

*İstanbul switch'inde vlan ve sub-ınt ayarları yapıldı.

# PROJE 1 
## STATIC ROUTING

Şehir (Routerlar) arasında static route yazıldı.

 1-İzmir'den İstanbul'a 

 2-Ankara'dan İstanbul'a 

 3-İstanbul'dan İzmir'e 

 4-İstanbul'dan Ankara'ya 

*İstanbul router'na IPV4 ve IPV6 için access-list yazıldı. 

*İstanbul switch'ine port-security ayarı yapıldı. 

# PROJE 2
## OSPF

*İstanbul,Ankara ve İzmir routerları arasında OSPF Config yapıldı.

*İstanbul routerında IPV4 ve IPV6 için access-list yazıldı.

*OSPF authentication yapıldı.

*Tüm switchlere port-security ayarı yapıldı.
