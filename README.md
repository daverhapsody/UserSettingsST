# UserSettingsST
These are the magic Dave's ST settings  :3333

The first thing you're gonna do is to delete the user folder (~/Library/Application Support/Sublime Text 3/Packages/User) and just delete it. Obv you'll have to install this immediately after ;)

To add these functions you'll have to activate the console (By using shift+cmd/ctrl+p and searching in it) and type this code.

import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by) 


It's cooooool, seal of approval <3 
I'm a Mac User, when it will be necessary I'll add the User folder path of Linux/Windows :)
