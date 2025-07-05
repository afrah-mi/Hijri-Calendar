# Hijri-Calendar
An interactive web-based Hijri calendar that maps each Islamic date to its corresponding Gregorian sunset-to-sunset range. Features include current month highlighting, tooltips on hover, and locked future months.

# About 🚀
This is an interactive web-based Hijri calendar that displays all 12 Islamic months in a clean, visually engaging grid format. Each day maps accurately to its corresponding Gregorian date, with special consideration given to sunset-to-sunset timing (Maghrib), and actual moon sightings, not mathematical predictions.

# Problem 🧩
Digital Hijri calendars today:
* Use plain, list-style layouts that are hard to read or old fashioned
* Are primarily Gregorian calendars with Hijri dates tacked on
* Purely Hijri calendars (that show 0 relation to georgian dates) are not applicable for daily life (since the georgian calendar is widely used)
* Show inaccurate dates by switching days at midnight rather than sunset (Maghrib) creating confusion for users
* Have discrepency for when the year starts, for example they do not specify if Muharram 1 begins on June 25 or June 26 (correct answer: neither!)
* Predicting furutre months using mathematical models, rather than traditionally following moon sightings, losing the culture of patience
* Do not actually display the moon, leaving users ignorant to the traditional understanding of how to tell the time of month through looking at the sky
Due to all these factors, the lunar, or hijri, calendar is pretty much discarded. The public often expresses frustration on not knowing when hijri days of importance will occur (ie. 10th Muharram, Ramadan, Eid, fasting etc.) and non-religious people have dificulty coordinating accomodations. Furthermore, this contributes to a growing disconnect from history and identity, as Gregorian systems dominate due to colonial legacy

# Solution 💚
This calendar solves those problems by:
* Visually appealing user interface in a grid-style
* Is primarily a Hijri Calendar
* Contains relevant connection to georgian dates so that one may use it in daily life
* Updating the current Hijri date daily at sunset (Maghrib), not midnight. And it makes this clear through an updating time in the bottom right corner.
* Using hover tooltips that clearly show the Gregorian date range that each Hijri day spans (ie. Muharram 1 begins June 25th at sunset, and ends June 26th sunset)
* Displaying only the confirmed current Hijri month (no predictions). The other months are locked and will open as the moon is sighted.
* Shows the phases of the moon so the user will be aware

# Social Impact 🌎
This project is an act of cultural preservation and decolonization. By creating a Hijri-first calendar that’s accurate and appealing, it helps reconnect users with their faith, history, and heritage. It's especially useful for Muslims living in non-Muslim majority countries who want to honor fasting schedules, spiritual dates, and cultural continuity.

# Setup and Usage 📆
1. Clone the repository
2. Open the calendar simply by writing main.html in the browser
Alternativley:
1. Download main.html, muharram.html, and the images folder.
2. Store it all in one folder
3. Open in VScode, right click on main.html and press Open with Live Server

# Status 👀
This is an ongoing project that will be updated. Some future features that will be added are the following:
- Launch into a proper website
- Live viewing of the current moon
- Hijri age calculator
- Animation that highlights the current day on the calendar
- Timer that shows how much time is left in a moon phase
- Informative sections (since certain months are locked until the moon sighting, instead of clicking at it leading to nothing, it will click and lead to an information page on traditions, knowledge about moons, history etc. This feature will allow the website to be an educational source for children as well as a functional calendar!)

# Screenshots 📸
![image](https://github.com/user-attachments/assets/77dbae64-d94e-4235-a292-031bcb544108)
![image](https://github.com/user-attachments/assets/5d7c6db4-e241-4021-94ab-6050639abefe)

