# wyhk-timetable-exporter-js

Userscript version of the wyhk timetable exporter

---

Ping does not provide the option to export the timetable as `.ics` format, guess I'll have to do it myself

It's just a simple script to request the timetable api to provide everything I need and want

## Screenshots

![Screenshot 2023-11-11 155223](https://github.com/BlissfulAlloy79/wyhk-timetable-exporter/assets/45236703/771711bb-952a-4fdd-805b-bdc2f54e7a6a)

![IMG_0440](https://github.com/BlissfulAlloy79/wyhk-timetable-exporter/assets/45236703/47db7378-a6a0-4611-9f82-98338358ece8)

## How it works

This userscript inserts button to the normal timetable web app interface

by clicking the buttons, the script will request the timetable apis and generate timetable files in `.ics` format where users can import them to various timetable applications

i.e. Apple Calendar, Google Calendar etc.

Unlike the Python version, you won't have to extract the cookie manually as this script will directly request the timetale api with the credentials of your session

