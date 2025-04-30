<!--
Autor: Fabio Weidner
Version: 1.0
Sektion: Meta & Systemstruktur
Veröffentlichung: April 2025
-->

# 🗺️ Visualisierung der Systemlogik der Kollektiven Räterepublik

> 📚 Dieses Dokument stellt die zentralen Prozesse und Strukturen der Kollektiven Räterepublik in grafisch orientierter Form dar – zur besseren Verständlichkeit des politischen Gesamtmodells.

---

## 🧭 Einleitung

Die Kollektive Räterepublik basiert auf einem systemisch rückgekoppelten Kreislaufmodell. Statt linearer Entscheidungswege folgen die Prozesse einer zirkulären Logik aus Wahl, Umsetzung, Kontrolle und Rückbindung.

---

## 🔄 Zyklus der politischen Mitbestimmung

```mermaid
graph TD
    Kollektiv((Kollektiv)) --> Kollektivrat[Kollektivrat]
    Kollektiv --> Bezirksrat[Bezirksrat]
    Kollektivrat -->|organisiert| Gruppenstruktur
    Bezirksrat -->|organisiert| Gruppenstruktur
    Gruppenstruktur --> Gruppen[Thematische Gruppen]
    Gruppen --> KleineRaete[Kleine Räte + Vorsitzende]
    KleineRaete --> GeschlossenerRat[Geschlossener Rat (Exekutive)]
    GeschlossenerRat -->|Umsetzung| Maßnahmen
    Maßnahmen --> Rückkopplung[Rückmeldung aus Bevölkerung & Gruppen]
    Rückkopplung --> Kollektivrat
    Rückkopplung --> Kollektiv
```

---

## 🏛️ Institutionelle Übersicht

```mermaid
graph LR
    subgraph Kollektiv
        Bürger[Kollektiv / Bürger:innen]
    end
    subgraph Räte
        Kollektivrat
        Bezirksrat
        Tribunalgericht
    end
    subgraph Gruppenstruktur
        GruppeA[Gesundheit]
        GruppeB[Wirtschaft]
        GruppeC[Kultur]
        GruppeD[Infrastruktur]
    end
    subgraph Exekutive
        GeschlossenerRat
    end
    Bürger --> Kollektivrat
    Bürger --> Bezirksrat
    Kollektivrat --> GruppeA
    Kollektivrat --> GruppeB
    Kollektivrat --> GruppeC
    Kollektivrat --> GruppeD
    GruppeA --> GeschlossenerRat
    GruppeB --> GeschlossenerRat
    GruppeC --> GeschlossenerRat
    GruppeD --> GeschlossenerRat
    Bürger --> Tribunalgericht
```

---

## 📦 Entscheidungspfade & Rückkopplung

```mermaid
graph TD
    Entscheidung[Entscheidung] --> Umsetzung[Umsetzung durch Exekutive]
    Umsetzung --> Wirkung[Gesellschaftliche Wirkung]
    Wirkung --> Feedback[Feedback aus Gruppen / Bevölkerung]
    Feedback --> Analyse[Analyse durch Kollektivrat / Gruppe]
    Analyse --> Revision[ggf. Revision / Anpassung]
    Revision --> Entscheidung
```

---

## 📌 Fazit

Die Visualisierung zeigt: Die Kollektive Räterepublik ist ein System zyklischer Politik – nicht Top-down, sondern feedbackbasiert, lernfähig und kollektiv getragen.

---


