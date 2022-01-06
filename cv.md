## rsschool-cv

# Anna A Demeshkevich
<img src="https://media-exp1.licdn.com/dms/image/D4D03AQEjjB6gNxjBTA/profile-displayphoto-shrink_800_800/0/1636722754136?e=1645660800&v=beta&t=LSc_2NwMECpu8wJoZThiHXZWLvX3eSO7UoVgXefVEts" width="200" height="200" alt='photo' />

### *Junior Full Stack Python Developer*

## Contact information:

**Address:** Minsk, Belarus;<br>
**E-mail:** *dem2a6@gmail.com;*<br>
**Phone:** *+375299759068* ;<br>
**GitHub:** [dem2an](https://github.com/dem2an)<br>
**LinkedIn:** [Anna A Demeshkevich](https://www.linkedin.com/in/anna-demeshkevich-23309a193)<br>
**Telegram:** [@Dem2an](https://t.me/Dem2an)<br>
**Discord Server:** ann_demeshkevich (@dem2an)


## Overall information

**Goal:** Study various technologies, language frameworks and platforms; create a portfolio of projects; improve skills; gain experience.<br>

**Priorities:** Python Backend, JS, CSS, HTML5 Frontend.<br>

**Strengths:** Desire to gain new knowledge; flexibility; hardworking; responsible; goal-oriented.<br>

**Work experiense:** <br>

|Period|Work Experience|
|:----:|----|
|July 2019 — july 2019|Practice in National Center of E-Service, e-Government|
|February 2020 — april 2020|Ernst & Young Belarus, Intern|
October 2020 — december 2020|Ernst & Young Belarus, Auditor's Assistant|
December 2020 — currently|Ernst & Young Belarus, Core Business Support Learning & Development|


## Skills

**Languages:**<br>

JavaScript - (in progress)<br>
Python - (in progress)<br>
C/C++ - (Basics)<br>
HTML/CSS - (Basics)

**DB:**<br>
SQL Server/ MySQL / SQL lite / Postgre SQL

**Frameworks:**<br>
Django

**Version control systems:**<br>
Git / Github

**Other programs and platforms:**
* Adobe Photoshop;
* Adobe Premiere Pro/Adobe Rush;
* Pycharm community;
* Visual Studio;
* Visuai Studio Code;
* Alteryx;
* MS Teams;
* SharePoint;
* Zoom Meetings;
* MS Outlook;
* Qualtrics;
* Mural;
* SuccessFactors;
* ServiceNOW;
* Cisco WebEx;
* Snagit.


## Code example:

~~~python
def search_by_date(feed, date, num):
    temp = [False, 0]
    new_feed = []
    date = date[:4]+'-'+date[4:6]+'-'+date[6:]
    for i in range(len(feed)):
        if date in feed[i]['published']:
            new_feed.append(feed[i])
            temp[1] += 1
            if temp[1] == num:
                break
        if temp[1] != 0:
            temp[0] = True
    if not temp[0]:
        logs.logger.debug('Items are not found')
        raise ValueError('Items are not found')
    return new_feed, temp[1]
~~~

## Projects

### RSS-parser - [link to Github](https://github.com/dem2an/RSS_reader/tree/dev)

<br>

## Education:

|Year|Type|
|:----:|:----|
|2017-2021|Academy of Public Administration under the aegis of the President of the Republic of Belarus, Management of Informational Resources;|
|2020|EY Summer Business Academy;|
|2021|"PostgreSQL" - Course Netology;|
|2021|"Introduction to SQL and working with a database" - Course Netology;|
|2021|"Basics of site layout" - Course Netology;|


## Languages:

### English — B1 — Intermediate
* I use language practice every day in my international team;
* Practice in Duolingo;
* EY english course.

