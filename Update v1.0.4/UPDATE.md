Changelog 02.07.2025

Fixed:
- Bug behoben: In locale_string.txt wurde bisher immer auch die erste Zeile (Originaltext) mitübersetzt. Jetzt bleibt die erste Zeile immer unverändert, nur die zweite Zeile (Übersetzung) wird erkannt und übersetzt.
- Bug behoben: Die Struktur (inkl. aller Leerzeilen) von locale_string.txt bleibt jetzt 1:1 erhalten. Es wird immer nur die zweite nicht-leere Zeile übersetzt, die Formatierung bleibt exakt wie im Original.
- Bug behoben: In itemdesc.txt und ähnlichen Dateien wurden Tabulatoren manchmal durch Leerzeichen ersetzt. Jetzt bleiben alle Tabs im gesamten Text immer erhalten und das Format bleibt exakt wie im Original.
- locale_string.txt Dateien werden jetzt korrekt übersetzt: Die Originalzeile bleibt immer unverändert, nur die Übersetzungszeile wird angepasst.
- Keine versehentliche Übersetzung der Originalsprache mehr.
- Kleinere interne Optimierungen an der Übersetzungslogik.

Performance:
- Massive Performance-Verbesserungen! Die Übersetzung großer Dateien ist jetzt bis zu 10x schneller.
- Deutlich reduzierter Speicherverbrauch und optimierte Ausnutzung moderner Mehrkern-Prozessoren.
- Selbst bei sehr großen Sprachdateien läuft der Prozess jetzt spürbar flüssiger und stabiler.

New:
- Neue Funktion: Beim Laden von locale_string.txt kann die gewünschte Codierung (z.B. EUC-KR, UTF-8, Windows-949) ausgewählt werden. Standard ist EUC-KR, aber der Nutzer kann die Codierung selbst bestimmen.

Update (New exe):  https://github.com/ShayRed/ShayHub-Translator

---

Changelog 02.07.2025 (EN)

Fixed:
- Bug fixed: In locale_string.txt, the first line (original text) was always translated as well. Now the first line always remains unchanged, only the second line (translation) is detected and translated.
- Bug fixed: The structure (including all blank lines) of locale_string.txt is now preserved 1:1. Only every second non-empty line is translated, the formatting remains exactly as in the original.
- Bug fixed: In itemdesc.txt and similar files, tabs were sometimes replaced by spaces. Now all tabs are always preserved throughout the text and the format remains exactly as in the original.
- locale_string.txt files are now translated correctly: The original line always remains unchanged, only the translation line is updated.
- No more accidental translation of the original language line.
- Minor internal optimizations to the translation logic.

Performance:
- Massive performance improvements! Translating large files is now up to 10x faster.
- Significantly reduced memory usage and optimized utilization of modern multi-core processors.
- Even with very large language files, the process now runs noticeably smoother and more stable.

New:
- New feature: When loading locale_string.txt, you can now select the desired encoding (e.g. EUC-KR, UTF-8, Windows-949). Default is EUC-KR, but the user can choose the encoding.

Update (New exe):  https://github.com/ShayRed/ShayHub-Transl
