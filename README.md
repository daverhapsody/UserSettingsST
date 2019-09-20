# Impostazioni Sublime-Text 3
In italiano:
Ciao, queste sono le impostazioni magiche di Sublime Text di **Dave** :333
Per prima cosa spostiamoci sulla cartella "**Packages**" di **Sublime Text**, 

```
Windows: %appdata%/sublime-text3/Packages
MacOs: /Library/Application\ Support/sublime-text3/Packages
Linux: /home/*tuoprofilo*/.config/sublime-text3/Packages
```

iniziamo a clonare la mia git all'interno della cartella **Packages** con:

```bash
git clone https://github.com/daverhapsody/UserSettingsST
```

A questo punto potremmo pensare di aver finito, e invece no, colpo di scena!Bisogna attivare package control, pertanto premete **ctrl+shift+p** e digitate inst.
A quel punto selezionate l'opzione in cui figura di installare il Package Control 

------

A questo punto, rimanendo con il programma aperto, vedrete che si installeranno piano piano tutti i super mega iper fantastici plugin :333
E che plugin ci ho messo? 

1. Un po' di snippets per LaTeX
2. Java Velocity: E' un set di snippets carine per Java
3. LaTeX BlindText e LaTeX snippet: Due set di snippets per LaTeX
4. Terminus: Abilita il terminale direttamente su Sublime
5. Package Control... Beh, grazie al *censura*
6. SnippetMaker: E' il plugin che consente di creare le snippets personalizzate COMPATIBILI CON ATOM
7. DeleteBlankLines: Praticamente prende tutte le righe vuote, ve le toglie per pulire il codice, molto figo

------

## For English Users :3333



These are the magic Dave's ST settings  :3333

The first thing you're gonna do is to delete the user folder (~/Library/Application Support/Sublime Text 3/Packages/User) and just delete it. Obv you'll have to install this immediately after ;)

To add these functions you'll have to activate the console (By using shift+cmd/ctrl+p and searching in it) and type this code.

import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by) 

It's cooooool, seal of approval <3 
I'm a Mac User, when it will be necessary I'll add the User folder path of Linux/Windows :)

