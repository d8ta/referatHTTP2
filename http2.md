# HTTP2
### Tomislav Anic / Daniel Raudschus

---

##Die Entwicklung von HTTP

---

##HTTP/0.9 (1991)
- GET
- URL

---

##HTTP/1.0 (1996)
- Statuscodes und Header

^ HTTP 1.0 Requests Sequentiell = Wartezeit weil der vorherige Request erst beendet werden muss

---

##HTTP/1.1 (Standard seit 1999)
- Persistant Connections

^ Verbindung wir solange aufrecht erhalten, bis client oder server diese explizit schliesst.
Vorteile ist eine reduzierung der Latenz.
HTTP 1.1 pipelining. Mehrere Request möglich, Aber: head-of-line blocking
Anforderungen werden blockiert, bis früherer Request fertig ist.
Die meisten Browser lösen dies durch mehrere Verbindungen zu einem Server.
Dies kann jedoch zu anderen Problemen führen, insbesondere erhöhte Belastung auf dem Server.


---

##HTTP/1.1 Header Beispiel
```
GET /tutorials/other/top-20-mysql-best-practices/ HTTP/1.1
Host: net.tutsplus.com
User-Agent: Mozilla/5.0 (Windows; U; Windows NT 6.1; en-US; rv:1.9.1.5) Gecko/20091102 Firefox/3.5.5 (.NET CLR 3.5.30729)
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,*/*;q=0.8
Accept-Language: en-us,en;q=0.5
Accept-Encoding: gzip,deflate
Accept-Charset: ISO-8859-1,utf-8;q=0.7,*;q=0.7
Keep-Alive: 300
Connection: keep-alive
Cookie: PHPSESSID=r2t5uvjq435r4q7ib3vtdjq120
Pragma: no-cache
Cache-Control: no-cache
```

---

##Eigene Protokolle z.B. SPDY (Google)
- Wenig neues bei HTTP
- Multiplexing
- Server Initialisierung

^ Server kann zusätzlich eigenstängig Übertragungen initiieren

---

##HTTP/2.0 (Mai 2015)
- IETF verabschieded HTTP/2.0

^ Internet Engineering Task Force

---

#Best Practice HTTP/1.1

- Spriting

^ Mehrere kleine Bilder werden in ein großes zusammenfassen

 - Inlining

^ JS und CSS aus HTML muss nicht extra übertragen werden
Nachteil: Keine externen CSS Files im Cache

- Concatenation

^ Zusammenfassen mehrerer js oder css files zu einem

- Sharding

^ Pro Host 6 Verbindungen erlaubt, durch Anfragen
mehrerer hosts auch mehr verbindungen

- Cookie-less Domains

^ Assests anderer domains werden ohne cookies übertragen, damit die Requests entlastet werden

---

#HTTP2
^ TOMIS Teil


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
