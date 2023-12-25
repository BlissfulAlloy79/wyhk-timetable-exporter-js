# wyhk-timetable-exporter-js

Userscript version of the wyhk timetable exporter

---

Ping does not provide the option to export the timetable as `.ics` format, guess I'll have to do it myself

It's just a simple script to request the timetable api to provide everything I need and want

## Screenshots

![Screenshot 2023-12-25 234729](https://github.com/BlissfulAlloy79/wyhk-timetable-exporter-js/assets/45236703/1e1a2ecf-ef27-4350-9d67-d97e5b43b3f7)

![Screenshot 2023-11-11 155223](https://github.com/BlissfulAlloy79/wyhk-timetable-exporter/assets/45236703/771711bb-952a-4fdd-805b-bdc2f54e7a6a)

![IMG_0440](https://github.com/BlissfulAlloy79/wyhk-timetable-exporter/assets/45236703/47db7378-a6a0-4611-9f82-98338358ece8)

## How it works

This userscript inserts button to the normal timetable web app interface

by clicking the buttons, the script will request the timetable apis and generate timetable files in `.ics` format where users can import them to various timetable applications

i.e. Apple Calendar, Google Calendar etc.

Unlike the Python version, you won't have to extract the cookie manually as this script will directly request the timetale api with the credentials of your session

## Installation

### Requirements

I recommend to use [Greasy Fork](https://greasyfork.org) + [TamperMonkey](https://www.tampermonkey.net/) for Chrome and other mainstream browsers on the computer

If you don't know what or how to use TamperMonkey, [this video helps](https://www.youtube.com/watch?v=8tyjJD65zws)

For Safari IOS users, you may use [Userscripts](https://github.com/quoid/userscripts) to load the userscipt

How to use Userscripts? [Follow the steps here](https://github.com/quoid/userscripts#usage)

### Install

Visit this link

https://greasyfork.org/scripts/483091-wyhk-timetable-exporter

to install the script, or you can download the script directly from this repo and import them manually

---

After successful installation, login to /timetables or /examtimetable site and see if the script have correctly loaded

If correctly loaded, for /timetables:

You should see 2 new buttons inserted below the selection boxes

<wait for image insertion

For /examtimetable:

You should see 1 new button inserted below the selection boxes

be remined that before exporting the exam timetable, select your exam first (。・ω・。)

![Screenshot 2023-12-25 234729](https://github.com/BlissfulAlloy79/wyhk-timetable-exporter-js/assets/45236703/1e1a2ecf-ef27-4350-9d67-d97e5b43b3f7)

