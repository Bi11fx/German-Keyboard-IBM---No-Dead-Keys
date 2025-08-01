# German-keyboard-no-dead-keys
Deutsches Tastaturlayout (IBM) ohne tote Tasten - German keyboard layout (IBM) without dead keys

# German (IBM) – Kein Dead Key Layout

Dies ist ein modifiziertes deutsches Tastaturlayout basierend auf dem offiziellen **"German (IBM)"** Layout von Microsoft.
In dieser Version wurden **alle toten Tasten entfernt**, um das Tippen von Akzenten und Sonderzeichen zu vereinfachen.

Das Layout wurde mit dem **Microsoft Keyboard Layout Creator (MKLC)** erstellt.

---

## 🔧 Enthaltene Dateien

| Datei                | Beschreibung                                 |
|----------------------|----------------------------------------------|
| `dekbdnd.klc`        | Layout-Quelldatei für MKLC                   |
| `setup.exe` / `.msi` | Installationspaket für Windows               |
| `dekbdnd.dll`        | Vom MKLC generierte Layout-Bibliothek        |

---

## 🔧 Was wird wohin installiert ?

| Datei                | Pfad                                                                                      |
|----------------------|-------------------------------------------------------------------------------------------|
| `dekbdnd.dll`        | C:\Windows\System32\; C:\Windows\SysWOW64                                                 |
| `regkey a0000407`    | Registry: Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Keyboard Layouts\  |

---

## ⚠️ Rechtlicher Hinweis

- Dieses Layout basiert auf dem "German (IBM)"-Layout von Microsoft und wurde mit dem offiziellen **Microsoft Keyboard Layout Creator (MKLC)** erstellt.
- Die erzeugten Dateien (`.klc`, `.dll`, `.exe`, `.msi`) können **urheberrechtlich geschützte Komponenten von Microsoft** enthalten.
- Dieses Projekt erhebt **keinen Anspruch auf Urheberrechte**, es wird **ohne Lizenz** und **ohne Gewährleistung** veröffentlicht –
  **ausschließlich zur praktischen Nutzung** für andere Nutzer.

🔗 Weitere Informationen:
- Microsoft Keyboard Layout Creator (MKLC): https://www.microsoft.com/en-us/download/details.aspx?id=22339
- Microsoft Copyright Policy: https://www.microsoft.com/en-us/legal/intellectualproperty/copyright/default.aspx

---

## 📥 Installation

1. Lade das passende Release herunter
2. Setup.exe starten
3. Das Layout sollte nun in der Taskleiste wählbar sein. Falls nicht in den Spracheinstellungen unter Tastatur nachschauen

---

## Deinstallation
1. Ein anderes Tastaturlayout wählen
2. Setup.exe starten
3. Remove wählen (Registry Eintrag wird dadurch entfernt)
4. Die `dekbdnd.dll` in `C:\Windows\System32` und `C:\Windows\SysWOW64` müssen meist selbst noch gelöscht werden.

---

## 🙋‍♂️ Warum dieses Layout?

Tote Tasten (wie ´ oder ^) sind für viele Nutzer hinderlich. Dieses Layout bietet eine „echte“ Tasteneingabe ohne Verzögerungen oder Kombinationslogik – ideal für Programmierer, Vieltipper und alle, die Sonderzeichen direkt eingeben möchten.

---

## ❗ Haftungsausschluss

Die Nutzung erfolgt auf eigene Verantwortung. Dieses Projekt ist **nicht mit Microsoft verbunden**. Es wird bereitgestellt **„wie gesehen“, ohne jegliche Garantie**.
