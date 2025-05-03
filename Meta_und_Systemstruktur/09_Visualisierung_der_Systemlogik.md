<p align="right">
  <img src="https://raw.githubusercontent.com/hades-dux/Kollektive-Raeterepublik/main/Meta_und_Systemstruktur/logo_offiziell.png" alt="Logo der Kollektiven Räterepublik" height="80">
</p>

<!--
Autor: Fabio Weidner
Version: 1.1
Sektion: Meta & Systemstruktur
Veröffentlichung: Mai 2025
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
   KleineRaete --> GeschlossenerRat[Geschlossener Rat - Exekutive]
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
        Bezirksräte
        KleineRäte[Kleine Räte]
    end
    subgraph Gruppenstruktur
        Außenpolitik
        Bildung
        Kunst
        Infrastruktur
        Auroraexpress
        Unterhaltung
        ForschungInnovation[Forschung & Innovation]
        Ernährung
        Gesundheit
        IntegrationMigration[Integration & Migration]
        WirtschaftProduktion[Wirtschaft & Produktion]
        Digitalisierung
        JustizRecht[Justiz & Recht]
        UmweltKlima[Umwelt & Klima]
        Kultur
        Sicherheit
        VerwaltungStruktur[Verwaltung & Struktur]
    end
    subgraph Exekutive
        GeschlossenerRat[Geschlossener Rat]
    end
    subgraph Judikative
        Tribunalgericht
        Bezirksgericht
    end
    Bürger --> Kollektivrat
    Bürger --> Bezirksräte
    Kollektivrat --> Außenpolitik
    Kollektivrat --> Bildung
    Kollektivrat --> Kunst
    Kollektivrat --> Infrastruktur
    Kollektivrat --> Auroraexpress
    Kollektivrat --> Unterhaltung
    Kollektivrat --> ForschungInnovation
    Kollektivrat --> Ernährung
    Kollektivrat --> Gesundheit
    Kollektivrat --> IntegrationMigration
    Kollektivrat --> WirtschaftProduktion
    Kollektivrat --> Digitalisierung
    Kollektivrat --> JustizRecht
    Kollektivrat --> UmweltKlima
    Kollektivrat --> Kultur
    Kollektivrat --> Sicherheit
    Kollektivrat --> VerwaltungStruktur

    Bezirksräte --> Außenpolitik
    Bezirksräte --> Bildung
    Bezirksräte --> Kunst
    Bezirksräte --> Infrastruktur
    Bezirksräte --> Auroraexpress
    Bezirksräte --> Unterhaltung
    Bezirksräte --> ForschungInnovation
    Bezirksräte --> Ernährung
    Bezirksräte --> Gesundheit
    Bezirksräte --> IntegrationMigration
    Bezirksräte --> WirtschaftProduktion
    Bezirksräte --> Digitalisierung
    Bezirksräte --> JustizRecht
    Bezirksräte --> UmweltKlima
    Bezirksräte --> Kultur
    Bezirksräte --> Sicherheit
    Bezirksräte --> VerwaltungStruktur

    Außenpolitik --> GeschlossenerRat
    Bildung --> GeschlossenerRat
    Kunst --> GeschlossenerRat
    Infrastruktur --> GeschlossenerRat
    Auroraexpress --> GeschlossenerRat
    Unterhaltung --> GeschlossenerRat
    ForschungInnovation --> GeschlossenerRat
    Ernährung --> GeschlossenerRat
    Gesundheit --> GeschlossenerRat
    IntegrationMigration --> GeschlossenerRat
    WirtschaftProduktion --> GeschlossenerRat
    Digitalisierung --> GeschlossenerRat
    JustizRecht --> GeschlossenerRat
    UmweltKlima --> GeschlossenerRat
    Kultur --> GeschlossenerRat
    Sicherheit --> GeschlossenerRat
    VerwaltungStruktur --> GeschlossenerRat

    Bürger --> Tribunalgericht
    Bürger --> Bezirksgericht
```

---

## 📦 Entscheidungspfade & Rückkopplung

```mermaid
graph TD
    Entscheidung[Entscheidung] --> Umsetzung[Umsetzung durch Exekutive]
    Umsetzung --> Wirkung[Gesellschaftliche Wirkung]
    Wirkung --> Feedback[Feedback aus Gruppen / Bevölkerung]
    Feedback --> Analyse[Analyse durch Kollektivrat / Gruppen]
    Analyse --> Revision[ggf. Revision / Anpassung]
    Revision --> Entscheidung
```

---

## 📌 Fazit

Die Visualisierung zeigt: Die Kollektive Räterepublik ist ein System zyklischer Politik – nicht Top-down, sondern feedbackbasiert, lernfähig und kollektiv getragen.

---
