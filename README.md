# RouterOS_ddns_updater
Dynamic DNS update Mikrotik Router

Yksinkertainen dynaamisen dns scripti Mikrotikin reitittimeen

<h2> Käyttö </h2>

Avaa updater_over_nat.txt tiedosto.

Määritä dynaamisen dns palveluntarjoajan antama käyttäjänimi

```
:local username "theddnsusername"
```
Määritä tähän dynaamisen dns palveluntarjojan käyttäjännimelle salasana
```
:local password "theddnspassword"
```
Määritä tähän palveluntarjoajan antama dynaamisen dns verkko-osoite.
```
:local hostname "blabla.dy.fi"
```

Lisätietoa: https://www.taisto.org/DDNS_p%C3%A4ivitysohjelmat
