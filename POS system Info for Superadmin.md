##### POS system doretmeli zatlar hatary boyunca:
1. ==Branch== - Magazyn doretmek
2. ==User== - Ulanyjy doretmek (Kassir, Skladcy, Oficant we sm..)
3. ==Warehouses== - Sklad doretmek (Warehouse - hakyky sklad we POS -kassa degisli harytlar)
4. ==Category== - Harytlaryn degislilik gornuslerini doretmek
5. ==Halls== - Her Branca degisli 1 hall doretmek
6. ==Tables== - Her Kassir ucin 1 table doretmek (One_to_One)
7. ==Menu item types== - Her branch ucin ayratyn MIT doretmek
8. ==Products== - Sklada giryan harytlaryn atlary we mukdary/olceg birligini doretmek (kg, litr we sm..)
9. ==Menu items== - Kassa haryt doretmek (Baha, mukdar branch we sm..)
10. ==Transactions add Products to Warehouse== - Nadip sklada haryt gosmaly?
11. ==Transactions add Products from Warehouse to POS== - Nadip kassa haryt gosmaly?
12. ==Transactions remove Products from Warehouse to Trash== - Nadip zaya harytlary musura zynmaly?
13. ==See Sellout, trash and remaining products== - Nadip Satylan, Skladdaky galan, Zayalanan, Zynylan harytlary gormeli 
14. ==test== (Transaction) - Sonky test prosesy

### 1. Branch

**Branch bul magazynyn ozi ady bilen bile bolup duryar. POS sistemada esasy roly Branch oynayar sebabi ahli asakdaky doreteli zadymyz belli bir branca catylmaly bolyar**.
### 2. User
Asakda *User* yagny ulanyjy doredenimizde hokmany bermeli rugsatlarymyz:
	admin ucin group:     ==PMGRP WVGRP== 
	Kassirlar ucin group:  ==GSGRP, PMGRP, WTGRP==
	User permission:        ==ON staff_status==
	User profile:               ==ON user_show_list==

### 3. Warehouse
Bul bolsa sklad doredenimizde bermeli argumentlarymyz:
	 Warehouse (Sklad):   type: Warehouse
	 POS (Kassa):              type: POS
	 SELLOUT:                   type: CONSUMER
	 ==Sellout bul satylan harytlary hasaba almak ucin ulanylyan ~Ayna bolup duryar==

### 4. Category
Categoriya bul harytlaryn gornusi bolup duryar
Asakda bolsa categ doredenimizde bermeli rugsadymyz:
	 ==Display: ON==
### 5. Halls
Hall bul hokmany ahli magazyn ucin doretmeli zadymyz bolup duryar, rugsatlar:
	 ==Is active: ON==
### 6. Tables
Bulam edil Halls yaly hokmany doretmeli zadymyz bolup duryar, rugsatlar:
	 ==Is active: ON==
### 7. Menu item types
Bulam edil yokardakylar yaly hokmany doretmeli zadymyz bolup duryar, rugsatlar: 
	 ==Show in screen view: ON==
### 8. Products
Products bul Sklada yagny Warehousa girmeli harytlaryn ady we mukdary/olceg birligi bolup duryar (kg, lt, karobka, packa we sm...)

### 9. Menu items
Menu item bul kassada yagny POS da gorunyan gonumen harydyn ozi bolup duryar, Menu item oz icinde birnace producty oz icine alyp bilyar mysal ucin:
	==Menu item: Kartoska 1kg:==
		==Products: kartoska kg, paket prazracny.==
Berilemeli rugsatlar:
	 ==Is active: ON==

### 10. Test (Transaction)