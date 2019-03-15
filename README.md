# welcome_aboard
Frequently Asked Questions for new members and introductory steps needed to join us.

Bemutatkozó PowerPoint prezentáció:
https://github.com/DatasRev/pr/blob/master/190227_budapest_py_meetup/datarev_intro_final.pdf

Telepítés
Érdemes figyelni a 32 bites és 64 bites verziók közötti különbségre bármit telepítesz, lehet hogy a default link a 32 bites telepítőre mutat.
https://www.anaconda.com/download/
1. Felrakni a Miniconda v. Anaconda programot  a C:\ Anaconda mappába (400mb vagy kb. 3000 mb) - a telepítés végén ne pipáljuk be azt, hogy add to PATH. 
Ha már fent van a gépeden az Anaconda, természetesen nem gond, ha nem a fenti elérési útvonalon van, de gondoltam, jobb, ha egységes. Általában igyekszünk a GitHubra feltöltött adatforrásokra hivatkozni, de ha nem így tesszük, akkor jobb, ha mindenkinek ugyanott vannak a forrásfile-ok, így nem kell mindig módosítani a scripteket.
2. Vezérlőpult - Rendszer és biztonság - Rendszer - Speciális rendszerbeállítások - Speciális - Környezeti változók -
A felhasználó változóhoz hozzáadni: C: \Anaconda,
tehát nem rendszerváltozó.
Én a Pythont-t https://www.python.org/downloads/ a C:\Python mappába szoktam feltelepíteni egyébként.
3. Felrakni a Visual Studio Code programot.
https://code.visualstudio.com/download
4. Regisztrálni a DataCamp-re (www.datacamp.com), mivel sokat használjuk, rengeteg képzése van, és ezek egy része ingyen is elérhető.
5. Mobilra feltenni a SoloLearn applikációt

Gyakori Hibaforrások:
1. Többféle Python vagy Anaconda van a gépeden:
Erre olyan megoldásunk van, hogy uninstall mind, majd újratelepítés.
2. Amikor létrehozol egy Python file-t, akkor a file neve ne egyezzen meg
egy library nevével, ne legyen pl. pandas.py. 
3. Egyes hibaüzenetekre megoldás lehet, ha frissíted az adott könyvtárat,
mert változott a nyelvezete ahhoz képest, hogy legutóbb használtad.
