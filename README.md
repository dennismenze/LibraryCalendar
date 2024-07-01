# LibraryCalendar
A script to create a calendar file (ics) from library account data (Köln, Kreuztal, UB Hagen)

(English below)

Das Script (siehe LibraryCalendar.ipynb) ermöglicht es
- sich nacheinander in mehrere Benutzerkonten der Bibliotheken Köln, Kreuztal und UB Hagen einzuloggen
- die Daten der ausgeliehenen Medien herunterzuladen
- fällige Medien automatisch zu verlängern
- aus den Daten pro Konto und Fälligkeitsdatum einen Termin in einer neuen Kalendardatei (ics) zu erstellen.

Die Kalendereinträge enthalten Informationen darüber, welche Medien fällig sind, wie viele Medien wie oft verlängert werden können und das berechnete maximale Fälligkeitsdatum.

Die ics-Datei kann dann in einem Kalenderprogramm (Thunderbird, Outlook, etc.) abonniert werden. Mit einem Cronjob kann das Skript z.B. einmal täglich ausgeführt werden.


(English version)

The script (see LibraryCalendar.ipynb) allows you to
- log in to several library accounts in Cologne, Kreuztal and UB Hagen one after the other
- download the data of the borrowed media
- automatically renew due media
- Create an event in a new calendar file (ics) for each account and due date.

The calendar entries contain information about which items are due, how many items can be renewed and how often, and the calculated maximum due date.

The ics file can then be subscribed to in a calendar program (Thunderbird, Outlook, etc.). A cron job can be used to run the script once a day.
