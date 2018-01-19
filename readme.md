##### Erster Login: raspberry - raspberrz
Beim ersten Login ist ein Benutzername und Passwort voreingestellt, das erstmal geändert werden muss. Doch dazu muss man sich einmalig Anmelden.
Benutzername ist „pi“ und Passwort „raspberry“. Hier kann es schon zum ersten Problem kommen. Ich habe das verzweifelt mehrmals eingegeben, bis ich gemerkt habe, dass standardmässig das englische Tastaturlayout eingestellt ist auf dem die beiden Buchstaben „y“ und „z“ vertauscht sind. Um sich einzuloggen muss man also auf „z“ drücken für das „y“ vom Passwort „raspberry“.

##### Benutzername und Passwort ändern:
Am einfachsten geht dies über die grafische Oberfläche des Konfigurationswerkzeugs. Dies startet man mit
```python
sudo raspi-config
```
(auch hier findet sich bei englischem Tastaturlayout der „-„ auf der Taste „ß“
