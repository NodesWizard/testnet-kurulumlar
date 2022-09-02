Minima node kurulumu çok basittir .. telefona bile kurulabilir ama biz telefonunuzu bu node ile meşgul etmenizi önermiyoruz ..
Gereksinimleri çok çok düşük günde 1 adet minima token kazanıyorsunuz… Fiyatı 0.60–1 dolar arası olması planlanıyor… Mainnet eylül demişlerdi ama uzayacak gibi duruyor..
Genelde herkes AWS ücretsiz üyelik açıyor minimayı oraya kuruyor.. aylardır 1 kuruş ödemedik bizde AWS’ye kurmuştuk… LINK
Digital ocean en dandik pakete kurabilirsiniz .. Google cloud ile kurmak isterseniz 9–10 dolarlık makine 1 gb ram 1 cpu bile yeterli olacaktır..
Videoda söylemedim fakat, Contabo da sunucunuz varsa örnek veriyorum içinde Stride , Source yada başka kurulu bir node varsa onun yanına da kurabilirsiniz
Aşağıdaki kodla kurulum başlatalım
```
wget -O minima_setup.sh https://raw.githubusercontent.com/minima-global/Minima/master/scripts/minima_setup.sh && chmod +x minima_setup.sh && sudo ./minima_setup.sh -r 9002 -p 9001
```
Başlattıkdan sonra aşağıdaki siteden üye oluyoruz

Incentive Program
Edit description
incentive.minima.global

Daha sonra üye olduğumuz yerden Incentice ID alıyoruz .. aşağıdaki koddaki XXX olan yere yapıştırıp terminalde giriyoruz.

curl 127.0.0.1:9002/incentivecash+uid: XXX
Daha sonra siteden kontrol ediyoruz log geldiyse olay bitmiştir..

