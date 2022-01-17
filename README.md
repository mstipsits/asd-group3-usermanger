# Advanced Software Development - UserManager

##Gruppe 3

- Waleed Al-Shaikhli
- Milidrag Ivkic
- Zorana Jevtic
- Michael Schneider
- Michael Stipsits
- Sükür Yavuz

[![Build Status](https://app.travis-ci.com/mstipsits/asd-group3-usermanger.svg?branch=master)](https://app.travis-ci.com/github/
mstipsits/asd-group3-usermanger)

## Funktionale Anforderungen


| ID  | Anforderungen                                                                                                                                             |
|-----|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| 100 | Der UserManager muss dem Benutzer die Möglichkeit bieten sich mit username und password anzumelden.                                                       |
| 110 | Wenn username oder password nicht mit den gespeicherten übereinstimmen muss das System die Fehlermeldung „username oder password nicht korrekt“ ausgeben. |
| 120 | Das System muss dem Benutzer drei Versuche zum Einloggen anbieten.                                                                                        |
| 130 | Wenn der Benutzer angemeldet ist muss der UserManager dem Benutzer die Möglichkeit bieten das Kennwort zu ändern.                                         |
| 140 | Wenn der Benutzer das Kennwort ändert muss das System dem Benutzer die Möglichkeit bieten das neue Kennwort zweimal einzugeben.                           |
| 150 | Wenn der Benutzer das Kennwort ändert und zweimal eingegeben hat muss das System die Kennwörter vergleichen.                                              |
| 160 | Wenn die verglichenen Kennwörter gleich sind muss das System das Kennwort aktualisieren                                                                   |
| 170 | Wenn die verglichenen Kennwörter ungleich sind muss das System die Fehlermeldung „Kennwörter nicht gleich ausgeben“.                                      |
| 180 | Wenn ein Benutzer eingeloggt ist muss das System dem Benutzer die Möglichkeit bieten seinen Account zu löschen.                                           |
 | 190 | Wenn der Benutzer den Account löschen will muss der Benutzer eine Sicherheitsabfrage „Wollen Sie den Account wirklich löschen“ bestätigen                 |
| 200 | Das System muss dem Benutzer die Möglichkeit bieten einen Account mit Vorname, Nachname, Benutzername und Kennwort anzulegen.                             |
| 210 | Wenn der Benutzer einen neuen Account anlegen will muss das System auf Existenz des Usernames prüfen.                                                     |
| 220 | Wenn der Username existiert muss das System die Meldung „Username existiert bereits“ ausgeben.                                                            |
| 230 | Das System muss dem Benutzer die Möglichkeit bieten auszuloggen.                                                                                          |

## Erweiterungen

| ID  | Anforderung                                                          |
|-----|----------------------------------------------------------------------|
| 250 | Das System muss das Kennwort verschlüsselt speichern.                |
| 260 | Das System muss den Benutzer nach 60 Sekunden Inaktivität ausloggen. |

## Nicht funktionale Anforderungen

| ID  | Anforderungen                                                                 |
|-----|-------------------------------------------------------------------------------|
| 300 | Der UserManager muss mit Java umgesetzt werden. Minimale Version ist Java 15. |
