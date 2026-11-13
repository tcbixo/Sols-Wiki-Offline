<a id="top"></a>
<div align="center">

<img src="docs/banner.svg" alt="Sols Wiki – Offline-Wiki für Sol's RNG" width="100%">

<img src="docs/tagline.svg" alt="Jede Aura mit Chance, Biom und Cutscene" width="620">

<a href="https://github.com/tcbixo/Sols-Wiki/releases/latest"><img src="https://img.shields.io/github/v/release/tcbixo/Sols-Wiki?style=for-the-badge&label=Beta&color=8f9bff&labelColor=0b0b16" alt="Version"></a>
<a href="https://github.com/tcbixo/Sols-Wiki/releases"><img src="https://img.shields.io/github/downloads/tcbixo/Sols-Wiki/latest/Sols-Wiki.exe?style=for-the-badge&label=Downloads&color=5ef2ff&labelColor=0b0b16" alt="Downloads"></a>
<img src="https://img.shields.io/badge/Windows-10%20%2F%2011-c79bff?style=for-the-badge&labelColor=0b0b16" alt="Windows">
<img src="https://img.shields.io/badge/Sprache-DE%20%2F%20EN-ffd36e?style=for-the-badge&labelColor=0b0b16" alt="Sprache">

<br><br>

<a href="https://github.com/tcbixo/Sols-Wiki/releases/latest/download/Sols-Wiki.exe"><img src="docs/download.svg" alt="Sols Wiki herunterladen" width="380"></a>

<sub>oder unter <a href="https://github.com/tcbixo/Sols-Wiki/releases/latest">Releases</a> · eine einzige Datei, kein Admin-Recht nötig</sub>

<br><br>

<a href="#-was-ist-sols-wiki"><b>Über die App</b></a> &nbsp;·&nbsp;
<a href="#-so-sieht-sie-aus"><b>Vorschau</b></a> &nbsp;·&nbsp;
<a href="#-installation"><b>Installation</b></a> &nbsp;·&nbsp;
<a href="#-was-liegt-in-diesem-repo"><b>Repo-Inhalt</b></a>

</div>

<br>

## ✦ Was ist Sols Wiki?

**Sols Wiki** ist eine Desktop-App für **[Sol's RNG](https://www.roblox.com/games/15532962292)** auf Roblox. Sie packt das komplette
Sol's-RNG-Wiki in ein schnelles, schön gestaltetes Programm – mit allen Auren, Biomen, Gears, Items, Quests und Cutscenes.
Nach dem ersten Start funktioniert alles **offline**, und neue Auren kommen automatisch über dieses Repo dazu.

<table>
<tr>
<td width="50%" valign="top">

### 🌌 Alles aus dem Wiki
**498 Auren** mit Chance, Biom, Bild, Cutscene und Rezept ·
**30 Biome** mit Dauer und Breakthrough ·
**38 Gears** und **181 Items** mit allen Zutaten ·
Quests, NPCs, Effekte, **88 Achievements** und **102 Titel**

</td>
<td width="50%" valign="top">

### 🎲 Selbst rollen
Auto Roll direkt im Hauptmenü, mit echten Chancen, Luck, Breakthrough,
Biom- und Tag/Nacht-Wechsel. Deine Sammlung, Gears und Auren-Crafting –
der Spielstand bleibt verschlüsselt auf deinem PC.

</td>
</tr>
<tr>
<td valign="top">

### 🎨 Im Sol's-RNG-Stil
28 animierte Biom-Hintergründe, Tier-Farben wie im Spiel, Cutscenes mit
angeglichener Lautstärke, Deutsch und Englisch, Textgröße, FPS-Regler
und vieles mehr in den Einstellungen.

</td>
<td valign="top">

### ⚡ Immer aktuell
Codes werden live geprüft, Achievement-Besitzer kommen live von Roblox.
Neue Auren und Bilder lädt die App selbst aus diesem Repo, und bei einer
neuen Version zeigt sie dir einen Update-Hinweis.

</td>
</tr>
</table>

## ✦ So sieht sie aus

<div align="center">
<img src="docs/demo.gif" alt="Auto Roll im Hauptmenü" width="100%">
<sub><i>Auto Roll im Hauptmenü – mit echten Chancen, Biom-Timer und Luck</i></sub>
</div>

<br>

<table>
<tr>
<td><img src="docs/screenshots/menu.png" alt="Hauptmenü"></td>
<td><img src="docs/screenshots/aura.png" alt="Aura-Detail"></td>
</tr>
<tr>
<td><img src="docs/screenshots/auras.png" alt="Auren-Liste"></td>
<td><img src="docs/screenshots/gears.png" alt="Gears und Rezepte"></td>
</tr>
</table>

## ✦ Installation

1. **[Sols-Wiki.exe herunterladen](https://github.com/tcbixo/Sols-Wiki/releases/latest/download/Sols-Wiki.exe)** und starten (am besten auf den Desktop legen).
2. Beim ersten Start lädt die App alle Bilder und Cutscenes (~5 GB) – das Fenster zeigt dir den Fortschritt.
3. Fertig. Ab jetzt startet die App in Sekunden, auch ohne Internet.

> [!NOTE]
> Windows kann beim ersten Öffnen „Der Computer wurde durch Windows geschützt“ anzeigen, weil die App nicht signiert ist.
> Dann auf **Weitere Informationen → Trotzdem ausführen** klicken.

<details>
<summary><b>Systemanforderungen</b></summary>

- Windows 10 oder 11, 64 Bit
- Microsoft Edge WebView2 (bei Windows 11 schon dabei)
- ca. 5 GB freier Speicher, Internet beim ersten Start

</details>

<details>
<summary><b>Häufige Fragen</b></summary>

**Wo landen die Dateien?** Unter `%LOCALAPPDATA%\Programs\Sols Wiki`, Einstellungen und Spielstand unter `%APPDATA%\SolsWiki`.

**Wie deinstalliere ich die App?** Einstellungen → *Deinstallieren*. Das entfernt die App, alle Bilder und die Einstellungen.

**Bekomme ich Updates?** Ja. Neue Auren und Daten kommen automatisch, für eine neue App-Version erscheint ein Hinweis mit Download-Knopf.

**Läuft das im Spiel mit?** Nein. Sols Wiki ist ein eigenes Programm und greift nicht auf Roblox zu.

</details>

## ✦ Was liegt in diesem Repo?

| Ordner / Release | Inhalt |
|---|---|
| `images/` | Alle Bilder der App, sortiert nach `auras`, `items`, `gears`, `biomes`, `titles`, `achievements`, `effects`, `npcs`, `quests` |
| `data/` | Die Wiki-Daten der App (Auren, Items, Biome …) – verschlüsselt, nur die App liest sie |
| `docs/` | Banner und Screenshots dieser Seite |
| Release **Beta x.y.z** | Die App selbst (`Sols-Wiki.exe`) |
| Release **Cutscenes** | Alle Aura- und Biom-Cutscenes (Videos), lädt die App beim ersten Start |

<p align="right"><a href="#top">↑ nach oben</a></p>

<img src="docs/wave.svg" width="100%" alt="">

<div align="center">

<sub>
Texte und Bilder stammen aus dem <a href="https://sol-rng.fandom.com/">Sol's RNG Wiki</a> (CC BY-SA) und gehören ihren Autoren bzw. den Machern von Sol's RNG.<br>
Sols Wiki ist ein Fanprojekt und steht in keiner Verbindung zu Sol's Studio oder Roblox. · made by <b>tcbi</b>
</sub>

<br><br>

<sub><b>English:</b> Sols Wiki is a free offline desktop wiki for the Roblox game Sol's RNG – every aura, biome, gear and item, cutscenes,
an aura roller and live codes. <a href="https://github.com/tcbixo/Sols-Wiki/releases/latest/download/Sols-Wiki.exe">Download for Windows</a>.</sub>

</div>
