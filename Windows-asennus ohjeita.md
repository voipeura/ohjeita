# Windows-asennus ohjeita

### Windowsin asennus OVA-tiedostoksi (suurinpiirtein)

1. Ensimmäisenä tietysti pitää ladata ISO-tiedosto
2. Sitten tehdä perusjutut Virtualboxista ja laittaa koneen asetukset kuntoon.
3. Kun Windows-asennus on siinä vaiheessa, että se kyselee maa-asetuksia, pitää kone laittaa auditointi tilaan. (CTRL+SHIFT+F3)

Sen jälkeen voi koneen asetukset ja muut laittaa kuntoon omalla haluamalla tavalla.
### Päivitykset ja "Ajurit"(GuestBoxAdditions) kuntoon ennen Syspreppiä!!
 
## *Sysprepin käyttäminen lyhyesti*

Graafisessa käyttöliittymässä Sysprep on helppo laittaa. Sysprep ohjelma aukeaa automaattisesti, kun olet laittanut koneen auditointitilaan.

Ainoa ongelma oikeastaan siinä on se, että vastaustiedostoa ei saa laitettua.

Voit kumminkin laittaa tarvittavat muut asetukset *(Generalize,OOBE,SHUTDOWN)*.

Komentokehotteen kautta hieman hankalampi *(Ainakin aloittelijalle)*.

1. Ensin täytyy mennä sysprep-kansioon CD komennon avulla komentokehotteessa.
2. "C:\Windows\System32\Sysprep" Kun olet päässyt tähän kansioon olet oikeilla jäljillä.
3. Sen jälkeen voit kirjoittaa: sysprep.exe /generalize /shutdown /oobe /unattend:akuankka.xml
(akuankka.xml on vastaustiedosto. Se ei ole pakollinen, mutta se helpottaa)

### Vastaustiedoston luomisesta
Se on suhteellisen helppoa, kunhan seuraa ohjeita tarkasti eikä mene valitsemaan WOW-tiedostoja. Ei se ole sen kummempaa pitää vain ladata yksi ohjelma ja katalogi. Sitten vain ruveta mätkimään asetukset kuntoon. Sen käytöstä laitoinkin tuonne aikaisempaan.