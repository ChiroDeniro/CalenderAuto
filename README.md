# 📅 CalenderAuto

Automatische kalender scripts voor KABK gerelateerde agenda's. Genereer `.ics` bestanden en importeer ze in Google Calendar.

---

## 📁 Bestanden in deze repo

| Bestand | Beschrijving |
|---|---|
| `kabk_academische_kalender.ics` | KABK academische kalender 2025-2026 |
-----

## 🚀 Optie 1 — Abonneren via URL (aanbevolen) oioijoijo

Je agenda blijft automatisch up-to-date als er iets wijzigt.

1. Ga naar [calendar.google.com](https://calendar.google.com)
2. Klik links op **+** naast *Andere agenda's*
3. Kies **Via URL**
4. Plak deze link:

**KABK Academische Kalender:**
```
https://raw.githubusercontent.com/chirodeniro/calenderauto/main/kabk_academische_kalender.ics
```
```

5. Klik op **Agenda toevoegen** — klaar! ✅

> 💡 Google herlaadt geabonneerde agenda's elke 12-24 uur automatisch.

---

## 📥 Optie 2 — Handmatig importeren

Gebruik dit als je de agenda eenmalig wil importeren zonder automatische updates.

1. Download het `.ics` bestand uit deze repo
2. Ga naar [calendar.google.com](https://calendar.google.com)
3. Klik op het ⚙️ tandwiel rechtsbovenin → **Instellingen**
4. Klik links op **Importeren & exporteren**
5. Kies het gedownloade `.ics` bestand
6. Selecteer in welke agenda je het wil importeren (maak een nieuwe aan voor makkelijk aan/uitzetten)
7. Klik op **Importeren** ✅

---

## 🔄 Agenda aan/uitzetten

Na het toevoegen kun je de agenda makkelijk aan- en uitzetten:

- Ga naar de linkerzijbalk in Google Calendar
- Klik op het **gekleurde bolletje** naast de agendanaam
- De agenda verdwijnt of verschijnt direct

---

## 🗓️ Wat zit er in de KABK kalender?

| Icoon | Betekenis |
|---|---|
| 🔴 KABK GESLOTEN | Gebouw dicht voor iedereen (feestdagen, wintervakantie) |
| 🟡 Beperkt Open | Ma t/m vr 8:00–17:00, za & zo gesloten |
| 📅 Vakantie info | Overzichtsblokken van alle vakantieperiodes |

---

## 🛠️ Scripts zelf draaien
```bash
# Clone de repo
git clone https://github.com/chirodeniro/calenderauto.git
cd calenderauto

# Genereer de KABK kalender
python3 generate_kabk.py

# Genereer de werkdagen kalender
python3 generate_calendar.py
```

De `.ics` bestanden worden aangemaakt in de huidige map.

---

## ❓ Problemen?

- **Link werkt niet?** Check of het bestand in de `main` branch staat op GitHub.
- **Events staan in de verkeerde agenda?** Verwijder ze en importeer opnieuw in een aparte agenda.
- **Agenda update niet?** Google herlaadt URL-abonnementen elke 12-24 uur. Je kunt niet handmatig forceren.
