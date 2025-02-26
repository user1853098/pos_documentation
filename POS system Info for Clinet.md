##### POS system doretmeli zatlar hatary boyunca (Ulanyjy/Klient ucin):

1. ==Products== - 
	Sklada giryan harytlaryn atlary we mukdary-ny/olceg_birligi-ni kesgitlemek (*kg, litr we sm..)
	Sklada islendik 1 harydy gosmak islesek ilkibasda products -da sol harydy doretmeli bolyarys.

2. ==Category== - 
	Harytlaryn degislilik gornuslerini(*kategoriyasyny) doretmek.
	Mysal: (Ayal kowus, Erkek kowus, Corek onumleri, Spirtli icgiler we sm..)

3. ==Menu items== - 
	Kassa (POS sistemanyn clinet tarapyndan goruner yaly) haryt doretmek (*Baha, mukdar branch we sm..)
	Menu item programmanyn esasy bolegi/ozeni bolup duryar sebabi ahli ekrana goyulyan towarlar menu item
	Egrede biz programma Products doredip menu item doretmesek onda programmanyn yuzunde bizin doreden harydymyz gorunmez.
	
4. ==Tables== - 
	Her Kassir ucin 1 table doretmek (One_to_One her magazynda in azyndan 1 table bolmaly)
	Table -y kassir-yn oturyan yeri diyip alsak hem bolor

5. ==Transactions add Products to Warehouse== - 
	Nadip sklada haryt gosmaly?

6. ==Transactions add Products from Warehouse to POS== - 
	Nadip kassa haryt gosmaly?

7. ==Transactions remove to Trash== - 
	Nadip zaya/gerekmejek harytlary musura zynmaly/ayyrmaly?

8. ==See Sellout, trash and remaining products== - 
	Nadip Satylan, Sklad-da galan, Zayalanan, Zynylan harytlary gormeli. (*mukdarlary bilen)

9. ==Orders== - 
	Zakazlary gormek. (Hacan alyndy, cykan baha we barcody)

10. ==Order details== - 
	Bul hem edil orders yaly yone has icgin giryar (Haysy harytlar alyndy we sm...)
	
### Warehouse bilen POS tapawudy?
Warehouse- sklad bolup duryar, yagny magazynyn icindaki dalde skladda duran harytlaryn ahlisi Warehouse -a degisli bolup duryar
POS- bul bolsa magazynyn icinde duran harytlar bolup duryar (*Skladdaky harytlar muna degisli dal!)
	
### Products bilen Menu item tapawudy?
Sistemamyzda esasan sklad bilen islemek ucin uly mumkincilikler bar egerde biz bul mumkinciliklerden doly
we dogry ulanjak bolsak onda Products bilen Menu itemyn tapawudyny bilmeli bolorys.

***Gysgaca aytsak: Products -> Warehouse; Menu Item -> POS;***

Yagny Menu_item POS sistemanyn yuzunde ~yagny menu-da gorulyan harytlar.
Products bolsa POS sistemanyn admin tarapynda skladda gorunyan harytlar bolup duryar.

***Products - Menu-da gorunmeyar; Menu item - sklada gorunmeyar.***

Sonun ucin ikisini biz Menu_item doredemizde birikdirmeli bolyarys.
**Widiolarda ahli zat gorkezilen.
**!Menu item oz icinde birnace producty alyp bilyar.