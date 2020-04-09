# Flight Web Scraper
Developed a web scraper that searches and compares various sites for best flight prices and emails users detailed list of round trip flights. This program sorts round-trip flights based on price, duration, and overall best offer based on all previously describes factors. This web scraper also predicts whether prices will change based on analysis of previous and current prices and will advise users to either buy now because prices are expected to go up or wait later since prices are expected to drop

## Set Up and Instructions 
1. First you must input your chromedriver path (around line 11)
2. Input your email (in username variable) and password (in password variable) at around lines 111 and 112 in order to receive emails of flights.
3. Input the email address of where you want to send it from and the email address of where you want the email sent to on line 133.

Now you have set up the web scraper now we can begin running the program.
<br>
1. Download or clone the project and change directory to the file.
2. Run the following command: python flightscraper.py
3. Input the flight information (Departing and Arriving Cities and Dates) and let the programming run.
<p align="center">
  <img width="574" alt="instructions" src="https://user-images.githubusercontent.com/16792195/78847022-7b736d80-79c2-11ea-9886-6440b59a3f42.png">
</p>
4. Once finished running, it will automatically send you an email with flight information.
