# Naše Arduino projekty
Rozhodl jsem se sepsat projekty, které provádím se svými dětmi a elektronikou. Úkoly jsou různě obtížné, začali jsme někdy v 5 letech, postupně se prokousáváme dále, jak věkem, tak obsahem.

[Literatury k Arduinu](https://arduino.cz/tag/ebook/) je všude dost, ale konkrétních příkladů co zkoušet s dětmi už je podstatně méně. Nejsem žádný expert na elektroniku, ale snažím se ji nabídnout i těm nejmenším dětem tak, aby je to bavilo.

> **Pozor, zápisky stále s dětmi stále doplňujeme.**

## Obecné 
Všechny nápady se týkají Arduina, což nutně nemusí být Uno R3, ale klidně i Pro mini a podobné. Pokud jsme použili jiný mikrokontroler, uvádím to. Součátky je možné nakupovat v ČR i v zahraničí (obvykle levněji). SW programujeme v [Arduino IDE](https://www.arduino.cc/en/main/software). Pro kreslení schémat využíváme [Fritzing](http://fritzing.org).

Ve všech projektech popisuji seznam součástek, ale Arduino board mezi nimi chybí, nechtěl jsem to jen neustále opakovat - prakticky všechny jsou za využití Arduina. Stejně tak neuvádím, že potřebujeme k projektu vodiče, nepájivé pole či napájení. Potřebujeme vždy.

## Řešené potíže
### "Permission denied" při pokusu nahrát program do Arduina na Linuxu
Uživatel musí být členem skupiny `dialout`.
``` bash
$ sudo usermod -aG dialout <user>
```

## Hraní s LEDkami
* [Ruční blikače](rucni_blikace/rucni_blikace.md)
* [Automatické blikače](automaticke_blikace/automaticke_blikace.md)
* [Semafor](semafor/semafor.md)
* [Night rider](night_rider/night_rider.md)
* Žížala
* RGB LED
* 8-segmentovky

## Ovládnutí displejů
* Znakový LCD displej
* OLED

## Infra
* Zmapování domácích vysílačů
* Infra a LED
* Zkoušení matematiky

## Čidla
* Teploměr s 8 segmentovým LED
* [Ultrazvukové měření vzdálenosti](meric_vzdalenosti/meric_vzdalenosti.md)
* Vlhkost půdy
* Vlhkost vzduchu, teplota, nadmořská výška

## [Robopixle](robopixle/robopixle,md)

## Plánujeme
* Domovní zvonek na střídavých 20V se dvěma melodiema
* Čidlo vlhkosti a teploty do koupelny
* Znalostní zkoušetko

