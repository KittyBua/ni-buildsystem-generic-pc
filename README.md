# NI \o/ - Neutrino für Android Boxen armv7 bauen - Termux mit Ubuntu dazu für den Bau ! 
https://www.dropbox.com/scl/fi/hh8ndoz36tckqstmydnim/termuxandroid-Ubu-ni.zip?rlkey=440ydark1cx0nmy9btjusvzuf&st=i8nc8v3p&dl=1
#

## 1) Repository clonen
```bash
git clone https://github.com/Yoshi1981/ni-buildsystem-generic-box.git
cd ni-buildsystem-generic-box
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
