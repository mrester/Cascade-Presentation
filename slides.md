# Cascade Persist Remove
--

## Was ist Cascade persist & remove?
---
* Begriff, der im Kontext von **ORM** (Object-Relational Mapping) verwendet wird
* Beschreibt Verhalten beim Speichern & Löschen von Objekten mit Beziehungen in einer DB
* Automatische Übertragung von Aktionen von einem übergeordneten Objekt auf seine verknüpften "Kindobjekte"
---

<!-- .slide:  data-transition="convex-in concave-out"-->
## Persist
* Übergeordnete Objekt und seine "Kindobjekte" werden in DB gespeichert 
---

<!-- .slide:  data-transition="convex-in concave-out"-->
## Remove
* Übergeordnete Objekt und seine "Kindobjekte" werden aus aus DB gelöscht 
--

## Vorteile
* Datenintegrität
* Vereinfachte Datenbankinteraktion
* Flexibilität
* Zeitersparnis
---

<!-- .slide:  data-transition="convex-in concave-out"-->
## Nachteile
* Schwierigkeiten bei der Datenmigration
* Performance
* Unerwartete Datenänderungen
--

## Anwendung in Entity Cart.php
![image](https://github.com/mrester/Cascade-Presentation/assets/95427647/fea07e54-4e1e-49d0-b839-a840d93f90ee)
---

<!-- .slide:  data-transition="convex-in concave-out"-->
## Anwendung in Entity CartProduct.php
![image](https://github.com/mrester/Cascade-Presentation/assets/95427647/8293b0db-82fe-40b2-ad0c-1ee498ffa9f1)
