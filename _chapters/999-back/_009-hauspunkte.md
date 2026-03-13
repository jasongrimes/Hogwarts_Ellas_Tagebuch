---
title: Hauspunkte
slug: hauspunkte
abstract:
---
<style>
  /* Das kleine Vorschaubild im Text */
  .diary-image {
    max-width: 100%;
    cursor: zoom-in; /* Ändert den Mauszeiger zu einer Lupe */
    border-radius: 3px;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
    transition: transform 0.2s ease;
  }

  .diary-image:hover {
    transform: scale(1.02); /* Bild hebt sich beim Drüberfahren leicht an */
  }

  /* Der abgedunkelte Hintergrund (anfangs unsichtbar) */
  .modal {
    display: none;
    position: fixed;
    z-index: 1000; /* Sorgt dafür, dass es über allem anderen liegt */
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.8); /* Dunkel, aber leicht durchsichtig */
    cursor: zoom-out; /* Zeigt an, dass man zum Schließen klicken kann */
  }

  /* Das vergrößerte Bild im Fokus */
  .modal-content {
    margin: auto;
    display: block;
    max-width: 90%;
    max-height: 90vh; /* Verhindert, dass das Bild über den Bildschirm ragt */
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%); /* Zentriert das Bild exakt */
    box-shadow: 0 0 20px rgba(0,0,0,0.8);
  }

  /* Das kleine X oben rechts */
  .close-btn {
    position: absolute;
    top: 20px;
    right: 35px;
    color: #f1f1f1;
    font-size: 40px;
    font-weight: bold;
    cursor: pointer;
  }
</style>


<img src="assets/images/general/Hauspunkte_transparent.png" alt="hauspunkte"
 onclick="document.getElementById('imageModal').style.display='block'">

<div id="imageModal" class="modal" onclick="this.style.display='none'">
  <span class="close-btn">&times;</span>
  <img class="modal-content" src="/assets/images/general/Hauspunkte_transparent.png">
</div>


<br>
<br>

**Punktebewegungen**

---

02.09.1950

- +3 Punkte für Hufflepuff
  - Leo brillierte im Zauberkundeunterricht und wusste Lumos und Alohomora.

- +5 Punkte für Slytherin
  - Genevieves Lumos funktionierte direkt perfekt und erstrahlte den ganzen Raum.

- -5 Punkte für Slytherin
  - Mildren kam zu spät zum Zauberkundeunterricht.

- +2 Punkte für Ravenclaw
  - Prof. Beery gab fälschlicherweise Klara Punkte, obwohl sie nur Leos Antwort wiederholt hat.

---

01.09.1950

- +20 Startpunkte für jedes Haus.

---
