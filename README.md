### Test Webprogrammierung 29.05.2024

**Name:** Mary Förster

**Anweisungen:** Beantworten Sie alle Fragen sorgfältig und vollständig. Die maximale Punktzahl für diesen Test beträgt 130 Punkte.

---

#### Teil 1: Planung eines Webprojektes (Relaunch)

**1.1.** Welchen wesentlichen Unterschied gibt es zwischen dem Relaunch einer bestehenden Webseite und der Planung einer neuen Webseite? (5 Punkte)
#
Bei einem Relaunch gibt es schon Vorhandenen Kontent mit dem man bei der Planung des Relaunch Arbeiten kann (behalten, löschen, verbessern) sowie design elemente Farben Schriften
#

Bei einer neuen Website muss ich die Komlette Struktur der Website Plannen sowie design elemente Farben Schriften erarbeiten
#
##
**1.2** Beschreiben Sie die wesentlichen Schritte bei der Planung eines Website-Relaunchs. (10 Punkte)
#

Analyse der Website 

Was bleibt, was geht, was funktioniert was funktioniert nicht ?

Texte und Bilder was bleibt ? was geht ? was muss überarbeitet werden ?

Wireframes der neuen Seiten Struktur erstellen 

Farben Schriften still elemente festlegen/behalten

Neues Screendesign Desktop/Mobil

Feedback runde

überarbeitung

Programmierung

Relaunch
#


**1.3** Warum ist es wichtig, eine Bestandsaufnahme der aktuellen Website durchzuführen? Nennen Sie zwei Gründe. (5 Punkte)

Um zu sehen was finktioniert was funktioniert nicht 

Was brauche ich nicht mehr

Was sollte ich hinzufügen 

Ist die Seite noch aktuell

Sollte ich Farben Schriften und Still elemente behalten 
#

**1.4** Welche Rolle spielt die Zielgruppenanalyse bei einem Website-Relaunch? (5 Punkte)

Eine Große rolle, ich muss wissen für wenn ich die website mache um zu wissen wie ich die Zielgruppe ansprechen kann, wie sie durch websiten navigieren UI/UX, und wie ich meine Inhalte darauf anpassen kann.
#
---

#### Teil 2: Git und Github

**2.1** Erklären Sie, was Git ist und wofür es verwendet wird. (5 Punkte)
Git ist eine Plattform auf der Programmierer und Entwickler zusammen Arbeiten können
Projekte Verwalten und Bearbeiten Code zusammenführen und an Projekten Parallel Arbeiten können, der Code wird auch online in der cloud gespeichert was eine Backup/Speichermethode
ist 

**2.2** Was ist Github und wie unterscheidet es sich von Git? (5 Punkte)

**2.3** Erklären Sie jeden der folgenden Begriffe: (10 Punkte)

* Repository: ein Repository ist ein Projekt wo alle Inhalte Gespeichert und verwaltet werden wie zb: html, css, java script, read me, php etc
#
* Branch: ein Branch ist eine eigene Oberfläche in der ich arbeiten kann. Ich kann zb in meinem eigen branche arbeiten und meine arbeit pushen ohne etwas im main branche zu überschreiben es wird nur euf meinem branch geändert die anderen im Projekt können denoch sehen was ich darin mache
#
* Commit: ich mache einen Commit in dem ich inhalte zuerst stage(sie also quasi in eine box lege) sie sprechend benne und dan einen Commit mache um meine Inhalte abzuschicken und später auch pushen zu können
#
* Merge: ein Merge ist wenn ich zwei branche zusammen Führe 
#
* Pull: Pull benutze ich um mir Erneuerungen im Projekt herunterzuladen
#
* Push: mit dem Push schicke ich meine Commits in die Cloud
#
* Clone: wenn ich ein Repository auf meinen Mac clone habe ich eine Kopie die mit der cloud verbunden ist
#
* Remote Repository / Origin: sind Originale
#
* Fetch: ich mache immer zuerst einen Fetch bevor ich etwas pulle um Konflikte zu vermeiden
#
* Konflikt: ein Konflikt kann entstehen wenn jemand zb an der gleichen componente arbeitet und sie es beide ohne absprache ins repo pushen dan gibt es einen Konflikt den man beheben muss in dem man sich zb für einen der beiden commits entscheidet.
#
---

#### Teil 3: CSS-Variablen nutzen

**3.1** Was sind CSS-Variablen und warum sind sie nützlich? (5 Punkte)

Css Variablen haben den sinn Arbeit zu vereinfachen und schneller zumachen
wenn ich eine css variable für eine farbe habe zb primary-color und ich benutze diese farbe überall auf meiner Website undd ich möchte die Farbe dan ändern habe ich den vorteil der Variable das ich die Farbe nur an einer stelle ändern muss und nicht überall einzelnt.
#

**3.2** Überarbeite den folgenden CSS-Code, indem du redundante Werte identifizierst und entscheidest, welche in CSS-Variablen ausgelagert werden sollten. Achte auf sinnvolle Variablennamen. (10 Punkte)

```css

/* Farben */


:root {
  ---color-white: #f0f0f0;
  ---color-blue: #007bff;
  ---color-grey: #333;
  ---border-radius-1: border-radius: 5px;
  ---border-radius-2: border-radius: 10px;
  ---padding-1: padding: 20px;
  ---margin-1: margin: 20px;
  ---main-font: font-family: Arial, sans-serif;
}

body {
  background-color: var(---color-white);
}

.header {
  background-color: var(---color-grey);
  color: var(---color-white);
}

.button {
  background-color: var(---color-blue);
  color: var(---border-radius-1);
  border: none;
  border-radius: var(---color-white);
  padding: 10px 20px;
  cursor: pointer;
}

.card {
  background-color: var(---color-white);
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-radius: var(---border-radius-2);
  padding: 20px;
}

/* Schriftarten */
h1 {
  font-family: var(---main-font);
}

p {
  font-family: var(---main-font);
}

/* Abstände */
.container {
  margin: var(---margin-1);
}

.header {
  padding: var(---padding-1);
}

.card {
  margin-bottom: 20px;
}

/* Größen */
.button {
  font-size: 16px;
}

.card {
  width: 300px;
}

```

---

#### Teil 4: Komponentenbasierte Elemente für Websites entwickeln

**4.1** Was versteht man unter komponentenbasiertem Webdesign? (5 Punkte)

Ich erstelle einzelne Komponenten die ich immer wieder verwenden kann und an jeder stelle einsetzen kann weil sie komplett alleine Funktionieren
#

**4.2** Nennen Sie zwei Vorteile der Nutzung von komponentenbasierten Elementen. (5 Punkte)
Schnelleres Arbeiten

überall einsetzbar

Klare Struktur
#

**4.3** Erstellen Sie ein einfaches Beispiel für eine komponentenbasierte HTML-Struktur (Kartenkomponente mit Bild, Titel, Text). (10 Punkte)

```html
     <div class="card__container">
          <div class="card">
            <div class="card__content">
              <div class="card__img">
                <img src="" alt="" title="" />
              </div>
              <div class="card__title">
                <h2>Card</h2>
              </div>
              <div class="card__text">
                <p>Lorem ipsum</p>
              </div>
            </div>
          </div>
     </div>
#
```
---

#### Teil 5: Container Queries

**5.1** Was sind Container Queries und wie unterscheiden sie sich von Media Queries? (5 Punkte)

Media Queries beziehen sich auf den ViewPort und Container Queries bezieht sich auf die Breite des Containers

Container Queries haben den Vorteil das ich nicht auf den ViewPort angewissen bin und ich kann sie somit unabhängig davon in meinem Code einbauen
#
**5.2** Beschreiben Sie eine Situation, in der Container Queries besonders nützlich sein können. (5 Punkte)

ein Beispiel Währe ich habe eine Text Box die unabhängig vom ViewPort umschalten sollte da der Text sonst viel zu eng und nicht mehr gut lesbar ist

oder wenn ich im nachhinein einen container schnell hinzufügen möchte ohne wieder groß die Media Queries bearbeiten zu wollen
#

**5.3** Erweitern Sie den folgenden **CSS-Code** um eine Container Query, sodass der Innenabstand eines Elements bis zu einer Containerbreite von 400px (width) 20px beträgt. (10 Punkte)

```css

.container {
 width: 500px;
}

.box {
  padding: 40px;
}

@container and (min-width:400px) {
  .box {
  padding: 20px;
}
}

/* Container Query */

```

```html
<div class="container">
  <div class="box">
    Dies ist eine Beispiel-Box mit variabler Schriftgröße.
  </div>
</div>
```

---

#### Teil 6: Praktische Aufgabe

Sie erhalten ein bestehendes Webprojekt auf Github und sollen einen Relaunch planen und teilweise umsetzen. Gehen Sie wie folgt vor: (30 Punkte)

0. Erstellen Sie ein Repository "Aufgabe6-Webprog" auf Ihren lokalen Rechner und kopieren Sie den Inhalt aus dem Ordner "Daten" hinein.
1. Erstellen Sie den "initial commit"
2. Erstellen Sie einen neuen Branch mit dem Namen "relaunch".
3. **Durchführen der folgenden Änderungen:**
   - **CSS-Variablen:** Definieren Sie sinnvolle CSS-Variablen und verwenden Sie diese in Ihrer CSS-Datei.
   - **Komponentenbasierte Elemente:** Entwickeln Sie eine einfache, komponentenbasierte HTML-Struktur für eine Kartenkomponente, die einen Titel, ein Bild und einen Text enthält.
   - **Container Queries:** Implementieren Sie eine Container Query, um die Schriftgröße der Kartenkomponente basierend auf der Containergröße anzupassen. Verwenden Sie eine Schriftgröße von 1rem bis zu einer Containerbreite von 540px.
4. **Committen Sie Ihre Änderungen:** Geben Sie nach jedem bedeutenden Schritt einen aussagekräftigen Commit-Namen an und committen Sie Ihre Änderungen.
5. **Merge:** Führen Sie einen Merge des "relaunch"-Branches zurück in den Haupt-Branch ("main") durch.
6. Erstellen Sie auf ihrem Github-Account ein neues öffentliches Repository mit dem Namen "Abgabe-Webprog".
7. Notieren Sie hier die URL zu Ihrem Repo auf Github: https://github.com/MaryFoerster/Aufgabe6-Webprog
8. Pushen Sie Ihr lokales Repository in das neu erstellte Remote-Repository.
9. Speichern Sie zusätzlich alle lokalen Dateien als ZIP-Datei "vorname-nachname.zip" und mailen diese an manuel@startmedia.at