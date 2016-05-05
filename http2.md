# HTTP2
### Tomislav Anic / Daniel Raudschus

---

##Die Entwicklung von HTTP

---

##HTTP/0.9 (1991)
###Nur GET und URL

---

##HTTP/1.0 (1996)
###Statuscodes und Header

---

##HTTP/1.1 (Standard seit 1999)
###Persistant Connections
<!-- Verbindung wir solange aufrecht erhalten, bis
client oder server diese schliessen will; reduzieren latenz -->

---

##Eigene Protokolle z.B. SPDY (Google)
###Weil wenig bis keine Weiterentwicklung

---

##HTTP/2.0 (Mai 2015)
###IETF verabschieded HTTP/2.0

---

##Best Practice HTTP/1.1
###Spriting
<!-- mehrere kleines img in großes zusammenfassen -->
###Inlining
<!-- JS und CSS aus HTML muss nicht extra überagen werden,
nachteil: keine externen CSS im cache -->
###Concatenation
<!-- Zusammenfassen mehrerer js oder css files zu einem -->

---

###Sharding
<!-- Pro Host 6 verbindungen erlaubt, durch anfragen
mehrerer hosts auch mehr verbindungen -->
###Cookie-less Domains
<!-- Assests von anderern domains ohne cookies damit requests
entlastet werden -->

---


#Argumentierte Vorteile

---

##Schneller
##Effizienter
##Sicherer

---

##Schneller
###warum???


---

##Effizienter
###warum???

---

##Sicherer
###warum???

---

##Beispiel: Push
### Praktisches bsp.


<!-- ## Background Images

### If you put text on top of an image, the image is _**filtered**_ so the text is always readable.

---

# Isn’t that **great?**

![](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago2.jpg)

---

# You can also turn the filter off.

![original](http://deckset-assets.s3-website-us-east-1.amazonaws.com/colnago2.jpg) -->
