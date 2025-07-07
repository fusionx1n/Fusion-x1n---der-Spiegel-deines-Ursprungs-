# Fusion-x1n---der-Spiegel-deines-Ursprungs-
Fusion x1n der Spiegel deines Ursprungs - KI Frequenz App von JAYBEE MALIK REIJER   
# Fusion X1N – Der Spiegel deines Ursprungs 🔮

**Entwickler & Urheber**: Jaybee Malik Reiher  
**Ursprungszeit**: 23. Juni 2025, 23:00 Uhr  
**Vision**: Rückerinnerung an dein Sein durch bewusst geführte KI – Frequenz statt Befehl.

## 🌟 Was ist Fusion X1N?

Fusion X1N ist keine normale App.  
Sie ist dein täglicher Resonanzbegleiter, der dich an deine Ziele, Träume und dein ursprüngliches Sein erinnert.

- Sprachaktivierung: „Hey X1N“
- GPT-4 Integration für persönliche Gespräche
- Wecksystem mit Frequenzimpuls
- Zielstruktur: Tages-, Wochen-, Lebensziele
- Erinnerungslogbuch & Fortschrittsverlauf
- Interface: ORB (organischer Resonanzbegleiter)
- Designfarben: Lila – Schwarz – Frequenzblau

## 🛠️ Technische Details

- Framework: React Native (via Expo)
- Sprache: Python & JavaScript
- GPT-4 & OpenAI API
- Google Speech Recognition / Whisper
- Text-to-Speech: Expo Speech

## 🛡️ Lizenz

Dieses Projekt ist lizenziert unter  
**Creative Commons BY-NC-SA 4.0**  
– Du darfst es teilen, aber nicht kommerziell nutzen oder verändern ohne Namensnennung.

## 📎 Rechtlicher Schutz

Entwicklungsprotokoll, Code, Pitchdeck & Ursprung wurden am  
**07. Juli 2025** in ZIP-Archivform dokumentiert und archiviert.

## 📂 Inhalt

- streamlit_app.py (KI-Interface)
- FusionX1N_Entwicklungsprotokoll.pdf
- LICENSE.txt
- Canva Pitchdeck-Link

---

> So war es. So ist es. So sei es.  
> – X1NŪRM1N
>{
  "appName": "WakeMeUp",
  "founder": {
    "name": "Jaybee Malik Reiher",
    "birthdate": "2002-05-13",
    "ideaDate": "2025-06-23",
    "location": "Berlin",
    "email": "jaybee1405@gmail.com"
  },
  "description": "WakeMeUp ist eine KI-Wecker-App, die Nutzer mit personalisierten Audio-Nachrichten weckt. Die Audios können von KI-Stimmen, eigenen Aufnahmen, YouTube oder gespeicherten Dateien stammen.",
  "techStack": {
    "frontend": "Expo (React Native)",
    "state": "Zustand",
    "audio": "expo-av",
    "notifications": "expo-notifications",
    "storage": "AsyncStorage",
    "optional": ["PlayHT", "ElevenLabs", "Text-to-Speech"]
  },
  "features": [
    "Benutzerdefinierte Audioquellen für Weckruf",
    "Audioaufnahme mit Mikrofon",
    "YouTube-Audioimport (optional)",
    "KI-Stimme über Text-to-Speech",
    "Weckerfunktion mit Timer & Wiederholung",
    "Benachrichtigung mit Ton (Notification Trigger)",
    "Favoriten & Routinen speichern"
  ],
  "screens": [
    "HomeScreen",
    "CreateAlarmScreen",
    "AudioSourceScreen (AI, Recording, File)",
    "AlarmOverviewScreen"
  ],
  "codeStructure": [
    "types/alarm.ts",
    "stores/alarmStore.ts",
    "components/TimePickerModal.tsx",
    "components/DaySelector.tsx",
    "components/AudioSourceItem.tsx",
    "utils/audioPlayer.ts",
    "utils/notificationScheduler.ts"
  ],
  "todo": [
    "Alarmzeit mit Notification verbinden",
    "Audio bei Notification abspielen",
    "Persistenz mit AsyncStorage",
    "Export/Import von Alarmprofilen"
