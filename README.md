# Grunnskipanir-Linux
### 1. Skoða skrár og möppur (ls)
#### Verkefni: Skrifaðu niður hvað þú sérð með hverjum rofa
* ls er notað til að sjá hvaða skrár og möppur eru í möppunni sem er í.
* ls -l sýnir meiri upplýsingar, eins og réttindi, stærð skráa og dagsetningar.
* ls -a sýnir líka faldar skrár.
* ls -lh gerir stærðir skráa auðveldari að lesa.
* ls -R sýnir innihald allra undirmappa.
  

  
### 2. Færa á milli mappa (cd)
#### Verkefni: Skrifaðu hvaða skipun notar þú til að fara úr /tmp aftur í heimasvæðið þitt.
**Svar:** Ég nota skipunina `cd ~` til að fara úr /tmp aftur í heimasvæðið.

### 3. Búa til möppur (mkdir)
#### Verkefni: Búðu til möppuna tilraunir/test1.
<img width="400" height="400" alt="linux Æfinga1" src="https://github.com/user-attachments/assets/daea578a-62a8-4e7a-820e-4d1faeea7214" />

### 4. Afrita skrár (cp)
#### Verkefni: Afritaðu möppuna verkefni1 yfir í verkefni1_backup.
<img width="2000" height="300" alt="1-2" src="https://github.com/user-attachments/assets/f8a003a1-5789-4f0b-9bae-60cd939328e0" />

### 5. Færa eða endurnefna (mv)
#### Verkefni: Endurnefndu verkefni1_backup í verkefni1_gamalt.
<img width="2000" height="300" alt="1-3" src="https://github.com/user-attachments/assets/f4c5282f-633c-40ad-8d3d-2afa80e40a6d" />

### 6. Eyða skrám eða möppum (rm)
#### Verkefni: Eyðu möppunni verkefni1_gamalt með staðfestingu
<img width="2000" height="400" alt="1-4" src="https://github.com/user-attachments/assets/1147a655-7d45-41f3-a8ad-a8e650f842e8" />

### 7. Skoða og birta texta (cat, echo)
#### Verkefni: Skrifaðu textann 'Ég er að læra Linux!' í skrá sem heitir texti.txt og skoðaðu hana með cat.
<img width="500" height="500" alt="5" src="https://github.com/user-attachments/assets/3dd3dd77-5853-4726-9e7d-2d2cf87d5b47" />

### Aukaáskorun
Gerðu skriftu (script) sem framkvæmir allar aðgerðirnar sjálfkrafa:
```#!/bin/bash
mkdir verkefni && cd verkefni
echo 'Halló heimur' > hallo.txt
ls -lh
cat hallo.txt
```
<img width="500" height="700" alt="6" src="https://github.com/user-attachments/assets/b83fe49a-32f0-4806-8c84-f1780e8daa83" />
<img width="500" height="700" alt="7" src="https://github.com/user-attachments/assets/7fee16ff-bf0e-4809-bf5a-c565733f7d8b" />



