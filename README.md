# LibraryCalendar
A script to create a calendar file (ics) from library account data (Köln, Kreuztal)

(English below)

Das Skript (siehe LibraryCalendar.ipynb) ermöglicht es
- sich nacheinander in mehrere Accounts der Bibliothek von Köln und Kreuztal einzuloggen
- sich die Daten über die ausgeliehenen Medien herunterzuladen
- Aus den Daten pro Account und Fälligkeitsdatum einen Termin in einer neuen Kalendardatei (ics) zu erstellen

Die Kalendereinträge enthalten Informationen darüber, welche Medien fällig, wie viele Medien verlängerbar sind und wie oft, und das berechnete maximale Fälligkeitsdatum.

Die ics-Datei kann dann in einem Kalendarprogramm (Thunderbird, Outlook, etc.) abonniert werden. Mit einem Cronjob kann das Skript z.B. einmal am Tag laufengelassen werden.


(English version)

The script (see LibraryCalendar.ipynb) allows you to
- log in to several library accounts in Cologne and Kreuztal one after the other
- download the data of the borrowed media
- Create an event in a new calendar file (ics) for each account and due date.

The calendar entries contain information about which items are due, how many items can be renewed and how often, and the calculated maximum due date.

The ics file can then be subscribed to in a calendar program (Thunderbird, Outlook, etc.). A cron job can be used to run the script once a day.
