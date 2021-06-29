# Cargurus-Data-Engineering-
This project is my introduction to Data Engineering. 


The project was to import used car prices to a dataframe.
Data Cleaning was also done to make it presentable to an Analyst/Scientist

Background
================
My roommate was selling his 2013 Lexus RX 350 so I decided to write a program that scrapes data from CarGurus: a site I frequently visit.


Known Issues:
=================
  1) The code doesn't take into account car manufacturers with two words. Only the first word will be taken. I'm yet to find out a method which doesn't involve hard-coding each manufacturer in (Alfa Romeo, Mercedes Benz, Aston Martin). The issue lies in seperating the model name from the manufacturer name as there isn't an indentifier called 'Model'
  2) There seems to be random entries into the list. The order of scraping doesn't match the order they are listed.
  3) I can't seem to get results from pages >1 . I've included the code to iterate over the pages in the website in a cell that is commented out. Every page seems to be giving the same result

Scope of Future Work
========================
I need to check if this issues appears across various used car sites. My next project will be on eBay motors.
