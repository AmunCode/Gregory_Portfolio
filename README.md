# Gregory_Portfolio
Examples of software projects

# [Top Movies](https://github.com/AmunCode/TopMovies)
Web app that stores top 10 favorite movies by ranking. 

- App uses TMDB API to pull information based on user entry.
- Information is stored into a SQL database.
- User may add, edit, and remove movies from their top 10.
- App is deployed on AWS EC2 instance.
  
Preqrequisites
---
`﻿altgraph==0.17.3`
`click==8.1.3`
`colorama==0.4.6`
`et-xmlfile==1.1.0`
`Flask==2.2.2`
`Flask-Login==0.6.2`
`future==0.18.2`
`itsdangerous==2.1.2`
`Jinja2==3.1.2`
`MarkupSafe==2.1.1`
`numpy`
`openpyxl==3.0.10`
`pandas`
`pefile==2022.5.30`
`pyinstaller==5.6.2`
`pyinstaller-hooks-contrib==2022.13`
`python-dateutil==2.8.2`
`pytz==2022.6`
`pywin32-ctypes==0.2.0`
`six==1.16.0`
`Werkzeug==2.2.2`
`Flask-wtf`
`Flask-sqlalchemy`
`Flask-bootstrap`

To Run
---
1. Instal Python 3.11
2. Install all files in repo into one folder.
3. `python main.py`

Demo Images
---
Main landing page displaying movies currently ranked. 
![image](https://github.com/AmunCode/TopMovies/assets/55643060/1c41b566-7649-48c0-87a9-fc6bd73a0927)

App displaying response to a user queury of movies with 'Marvel' in the title. 
![image](https://github.com/AmunCode/TopMovies/assets/55643060/db5e9cc9-4ebc-4cc3-868d-6d9afadc1563)

Edit screen to add personal rating and review comments.
![image](https://github.com/AmunCode/TopMovies/assets/55643060/98e9452d-9988-48fc-9780-f11bd4e7e68c)

Updated page with 'Captain Marvel' now ranked.
![image](https://github.com/AmunCode/TopMovies/assets/55643060/52c2ccd4-dda2-4b0e-b64c-a1f348b8b3c5)

Hovering on the ranking card will flip the card to reveal update and delete option. 
![image](https://github.com/AmunCode/TopMovies/assets/55643060/37194e83-3e6e-49f5-9ab4-358340a2d24d)


TODO
---
- Add user accounts and credentials
- Add AI movie recommendation based on current top 10 movies.


# [Jeggy](https://github.com/AmunCode/Jeggy)
Auctions scraper to pull and analyze BSstock auction inventory manifests for purchashing opportunities

- Automates a time consuming task from hours down to minutes
- OOP example: turns each item of each auction into an object. 
- Multi-threading to speed up scraping process. 

Jeggy Demo Images
---
Very simple interface with dropdown menu selection. 
![Opening Menu](https://user-images.githubusercontent.com/55643060/150057725-dc15fa99-da7a-4481-8a09-0cd3e919df7f.png)

Filtered Output Menu.
![Filtered Excel Output Menu](https://user-images.githubusercontent.com/55643060/150058491-51645fe3-c36a-4ad5-8df7-8ba699af7a2e.png)


# [CHUBU](https://github.com/AmunCode/CHUBU)
App automates the process of uploading tracking and invoice information into CommerceHub.

- More cost effective than EDI files 
- Reduced the labor cost with process automation
- uses Chrome driver and HTML tags for navigation. 

CHUBU Demo Images
---
Chrome under the control of app.
![Chrome controlled program](https://user-images.githubusercontent.com/55643060/150470495-d560d78b-b9fc-412a-9ff9-7d7edc27a7f0.png)


