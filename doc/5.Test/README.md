# Z čeho bude písemná práce
Vše co bylo před tím.
 - https://github.com/LukasMazl/SPSMB-PRO-2021/tree/main/doc/1.Test
 - https://github.com/LukasMazl/SPSMB-PRO-2021/tree/main/doc/2.Test

## OOP
 -  Jaké jsou základní vlastnosti OOP? - encapsulace, dedicnost, polymorfismus
 -  Zapouzdřenost -
 -  Dědičnost - rodic a dite
 -  Polymorfismus - více pohledů na jeden objekt
 -  Využití interface - deklarace metod
 -  Využití abstract class - má definici i deklaraci, 
 -  Rozdíl mezi interface a abstract class - interface má deklaraci, abstract class má definici i deklaraci

## Desktop (JavaFx)
 - Co je Event? - akce co se nestala
 - Co je Listener? - vykoná event
 - Základní komponenty - ChoiceBox, Button, Label, TextField

## Kolekce
- Collection - způsob jakým dinamicky pracovat
- Map - 
  - HashMap
  - Iterace
 ```java
   for(Map.Entry<String, String> entry: map.entrySet()) {
     System.out.println("key: " + entry.getKey() + ", value: " + entry.getValue());
   }
 
 ```
 
- List - list se jakjoliv rozšiřuje
  - ArrayList
  - LinkedList
- Set - zajišťuje unikátnost
  - HashSet - 

## Práce se soubory
- Kdo je zodpovědný za zápis do souboru? - operační systém
- Co je zámek? Kdo ho vytváří? - zajistí že nikdo ho nemůže zapisovat kromě programu, operační systém
- Inputstream - data které vchází do aplikace
- Ouputstream - data které odchází

## Vlákna
 - Co je vlákno? - umožňuje paralelismus, minimálně jedno vlákno
 - Jaké mohou nastat problémy? - nekonsistence
 - K čemu slouží slovíčko synchronized? - aby nedošlo k nekonsistenci
 - rozdíl mezi metody start(), run() a join() - join nechává doběhnout thread, run spouští

## Socket a aplikační vrstva
- K čemu slouží socket? - ke komunikaci buď mezi procesi nebo k různý komunikaci
- kdo vytváří socket? - operační systém
- Jaký je rozdíl mezi TCP protokolem a HTTP protokolem? - TCP na čtvrté vrstvě, HTTP aplikační vrstva je na úrovni aplikace
- Pomocí čeho získáte příchozí data? - Inputstream

## Obecné
- Program - to co je uložený na disku
- Proces - instance programu
- Vlákno - běží minimálně 
