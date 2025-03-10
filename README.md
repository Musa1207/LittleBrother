LittleBrother
=

LittleBrother est un outil de collectes d'informations (OSINT) qui vise à effectuer des recherches sur une personne française, suisse, luxembourgeoise ou belge. Il fournit divers modules qui permettent des recherches efficaces. LittleBrother ne requiert pas de clé API ni d'identifiant de connexion.

![](https://i.ibb.co/YdvfVPw/Capture.png)

Disclaimer
=
LittleBrother a été développé pour faire des recherches sur soi-même et pour voir les informations privées et sensibles que l'on peut laisser derrière sur les réseaux sociaux. Je n'encourage en aucun cas l'utilisation de cet outil sur une autre personne que soi-même ou d'utiliser cet outil à mauvais escient.

Discord
=
Si vous avez des questions, des idées, des problèmes concernant LittleBrother ou si vous voulez juste suivre l'avancement de ce projet.  
- [Serveur Discord](https://discord.gg/r8GvsYM)

Nouveautées version 6.0
=
- En plus (+)
	- Un fichier 'requirements.txt' a été ajouté.
	- Une nouvelle interface.
	- Un nouveau module d'OSINT a été ajouté, le module 'Profiler' remplace la base de données et de 'Dox maker' dans la version anterieur de LittleBrother. Ce module permet de créer un profil et de récupérer des informations sur les sites définis par l'utilisateur, de sauvegarder ces données et d'afficher les derniers post publiés sur les réseaux (filtrés selon les dates de publication).
	- De nouveaux services de recherche (Annuaires) ont été ajoutés selon la localisation de l'utilisateur. LittleBrother utilise votre IP pour déterminer le pays dans lequel vous vous trouvez. En aucun cas votre IP ou autre information privée sera partagé. Vous pourrez choisir un autre pays que le votre pour centraliser vos recherches.
	- Recherche Instagram et LinkedIn intégrés à 'Personne Lookup'.
	- Un nouveau module 'Employés recherche' qui permet de faire de trouver des personnes via une entreprise et une ville.
	- Les modules de recherche d'informations Instagram et Facebook ont été améliorés pour extraire plus d'informations.  

- En moins (-)
	- Certaines librairies python (dnspython, socket et smtplib) ont été supprimées pour cette version.
	- 'Social engineering tool' a été modifié pour 'Other tool' il ne comporte que le module de brute force d'un Hash.
	- Les modules 'Spam Email' et 'SMS' ont été retirés de LittleBrother.
	- Le module de création de Dox 'Dox maker' a été retiré de LittleBrother.


Compatible
=
- Windows
- MacOS
- Linux

Python version:
=
- Python3

Python Modules
=
- requests
- bs4
- terminaltables
- colorama


Installation Linux
=
    sudo apt install git python3
    git clone https://github.com/Lulz3xploit/LittleBrother
    cd LittleBrother
    python3 -m pip install -r requirements.txt
    python3 LittleBrother.py

Installation Windows
=
- 1. Download [LittleBrother](https://github.com/lulz3xploit/LittleBrother/archive/master.zip)
- 2. Download [python 3](https://www.python.org/downloads/release/python-380/) 
- 3. Install Python 3 with "Add to path" options.
- 4. Unzip LittleBrother (master.zip)
- 5. Open CMD and execute:
```
    cd LittleBrother-master
    python -m pip install -r requirements.txt
    python LittleBrother.py
```

Features
=
 - Lookup:

	- Phone lookup
	- Email lookup
	- Last name / First name lookup
	- Surname lookup
	- Addresse lookup
	- Mail ip locator
	- Ip locator
	- Bssid locator
	- Exif read
	- Google search
	- Twitter
	- Instagram
	- Facebook
	- LinkedIn employee search (New !)
	- Hash Bruteforce (New !)

 - Autre outils:

	- Hash Bruteforce

- Profiler (New !)
	- Profiler an profile
	- Database management
	- Profile creator

Contributors
=
❤️ [H3L](https://github.com/lrhel) ❤
