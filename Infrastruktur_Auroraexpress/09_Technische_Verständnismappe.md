# ⚙️ Technische Verständnismappe – Auroraexpress Infrastruktur

## Zielsetzung
Diese Mappe dient technischen Teams, Herstellern, Zulieferern, Planungsbüros und Systementwicklern als Grundlage für die **korrekte bauliche und funktionale Umsetzung** des Auroraexpress-Systems.

---

## 1. Infrastrukturquerschnitt (E0–E4)

| Ebene | Nutzung | Beschreibung |
|-------|---------|--------------|
| E0 | Güterverkehr | Magnetschwebebahnen für Container, Recycling, Großfracht |
| E1 | Personenverkehr | Auroraexpress-Pendelverbindungen, Schlafmodule |
| E2 | Mikromobilität | Fahrräder, E-Roller, Fußwege |
| E3 | Sonderlogistik | Notfallfahrzeuge, Rettungsinfrastruktur |
| E4 | Vertikalverkehr | Drohnen, Luftrettung, Expresslogistik |

---

## 2. AUX-Knoten: Funktionen & Module

| Einheit | Funktion |
|--------|----------|
| AUX-Core | Personenhub (Umstieg, sozialer Raum, Terminal) |
| AUX-Depot | Logistikdrehscheibe für Güter, Container, Versorgung |
| AUX-Sync | Verbindung zwischen Ebenen (z. B. E1↔E0) |
| AUX-Move | Mikromobilitätsstation (Verleih, Ladepunkte) |
| AUX-Maintain | Wartung, Systemcheck, Energie-Backup |

---

## 3. Gerätestandards & Schnittstellen

- Containerstation: Andockrahmen, Strom-/Datenschnittstellen
- Zugmodule: Modularer Aufbau, Energieversorgung durch Unterbodeninduktion
- Sensorik: Temperatur, Beladung, Sicherheit (offene Schnittstellen via Aurora-API)
- API-Protokolle: Für Drittgeräte (z. B. Verladekräne, Wartungseinheiten)

---

## 4. Redundanz & Notfallsysteme

- Schattennetz aktivierbar bei Ausfall oder Überlastung
- Backup-Stromversorgung durch Solarpuffer & Mikrokernreaktoren
- KI-gestützte Umschaltung bei Netzausfall (Plattform Aurora)

---

## 5. Dateninfrastruktur

- Aurora-Plattform = zentrales Steuersystem
- Verschlüsselte API für Produzenten, Städte & Verwaltung
- Blockchain-Logistikdokumentation
- Zugriffsschichten (Betrieb ↔ Wartung ↔ Bürgeranzeige)

---

> Diese Mappe ist für Schulungen, technische Ausschreibungen und Abstimmung mit Herstellern vorgesehen. Visualisierungen sind in Anhang B des Hub-Handbuchs enthalten.
