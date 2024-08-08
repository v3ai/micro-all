These files contain all the work Rhett Applestone has done in the summer of 2024 for the MIT-NSE Geiger Project

We use kicad for PCB design, and freecad primarily for 3d modeling, and engineering drawings. Although now ondsel (a freecad derivitive)
seem much easier to use an more polished and uses the same file format as freecad. 


For linux (mint)

### Installing Kicad
```
sudo add-apt-repository ppa:kicad/kicad-8.0-releases
sudo apt update
sudo apt install kicad
```

### Installing Freecad

```
sudo rm /etc/apt/preferences.d/nosnap.pref

sudo apt install snapd -y

sudo snap install --edge freecad

snap refresh
```

### Installing Ondsel with no account 

go to their github and download correct release https://github.com/Ondsel-Development/FreeCAD/releases





