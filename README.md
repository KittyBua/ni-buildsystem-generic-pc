# NI \o/ - Neutrino für PC+PI+ Phones mit Termux+proot+x11 - z.b. T-Phone 2 Pro (funktioniert 100%) - Wlan noch in Beta bei Smartphons - lan Adapter funktioniert ! #

## 1) Repository clonen
```bash
git clone https://github.com/KittyBua/ni-buildsystem-generic-pc.git
cd ni-buildsystem-generic-pc
```

## 2) Prerequisites und Dependencies erfüllen.
Siehe Makefile!


## 3) Build konfigurieren
```bash
make local-files
```

## 4) Neutrino bauen
```bash
make neutrino
```

## 5) Neutrino starten
```bash
make run
```

## 6) Aktualisieren und sauber machen
```bash
make update
make clean
```
