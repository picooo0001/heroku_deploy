## Description:
This is the official repo which gets pushed on the heroku server. 
There have been some complications with the old repo and heroku deployment, thats why this "thinner" repo is used for official deployment on heroku.
The old repo switched to private now.

Here is the URL:
https://tourplanningprod-f0de16b785fb.herokuapp.com/

The webapp consists of 1 login page and 3 subpages.

- Tourcreation:
  - Create tour

- Tour Kalendar:
  - List Tours with FullCalendar
  - Drag and Drop events (change date, time, duration)

- modify tours:
  - Change address, kolonne
  - delete date

Structure:
  - The frontend is written in HTML, CSS, Bootstrap
  - Frontend functions are written in JS
  - Those are connected to Flask
  - There is a PostgreSQL database to save tours and modifications
  - The communication between Flask and the database is written with SQLAlchemy


