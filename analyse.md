# Analyse von commits

## Gute commits:
Add login validation
Refactor Calculator for readability
Remove unused imports
Improve performance
Fix issue #23
Add null check
Update Calculator
Handle edge cases
Rename variables
Adjust logic
Improve readability

## Unübersichtliche commits:
Update
Fix bug
stuff
Changes in app
final version
Refactor code
Cleanup
Small fixes
Temporary fix


1.Add login validation: Gut, weil es sagt, was neu hinzugefügt wurde also ist verständlich.
2.Fix issue #23: Gut, zeigt genau welches Problem gelöst ist, leicht nachzuchecken.
3.Remove unused imports: Gut, erklärt die Bereinigung, man weiß sofort warum.
​

## Verbesserung
# Update:
* Unklar: Man weiß nicht, was geändert wurde. Es kann alles Mögliche sein.
* Fehlende Info: Welche Stelle im Code oder in der App ist geändert worden und warum.
* Kontext ok: In einem Test‑Branch nur für dich selbst, wenn du eh genau weißt, worum es geht.
* Besser: „Update Startseite‑Layout“ oder „Update Login‑Prüfung für Tokens“.


# Fix bug:
* Unklar: Man weiß nicht, welcher Fehler gemeint ist.
* Fehlende Info: Wo der Fehler war und was passiert ist (z.B. Absturz bei leerer Eingabe).
* Kontext ok: Wenn du mehrere kleine Commits machst, die später zu einem sauberen Commit zusammengefasst werden.
* Besser: „Fix Absturz beim Speichern leerer Notiz“ oder „Fix falsche Seitenzahl in Listenansicht“.


# Changes in app:
* Unklar: „Änderungen“ sagt gar nichts Konkretes.
* Fehlende Info: Welche Seite, welches Feature oder welcher Teil der App wurde verändert und warum.
* Kontext ok: Ganz kurz im eigenen Branch, bevor du ordentliche Commit‑Nachrichten daraus machst.
* Besser: „Change Navigation auf Startseite zu Bottom Tabs“ oder „Change Farben auf neues Firmen‑Design“.


# Small fixes:
* Unklar: Man weiß nicht, was genau repariert wurde und wie wichtig es ist.
* Fehlende Info: Ob es z.B. nur ein Rechtschreibfehler, ein Layout‑Problem oder ein Logikfehler war.
* Kontext ok: Wenn du gerade experimentierst und viele winzige Änderungen machst, die du noch aufräumen willst.
* Besser: „Fix Rechtschreibfehler in Login‑Fehlermeldung“ oder „Fix Button‑Ausrichtung im Einstellungs‑Screen“.


## Regel
* Auf Deutsch
* Nur das Wichtigstste
* Kurz formuliert
z.B.: Anmeldeformular Design