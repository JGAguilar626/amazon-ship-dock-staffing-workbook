<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/6bc1b670-8ad4-46ca-9cb5-18471c7ac556" width="640" height="400"></div>

# <div align="center">amazon-shipdock-staffing-workbook</div>
This project consists of a Microsoft Excel workbook that can be used by Amazon Fulfillment Shipdock department leadership to plan and visualize labor allocation.

## Project Description
This project consists of an Excel (.xlsx) workbook with 4 worksheets.

**MainBoard**: This worksheet is the digital version of a real-life whiteboard-on-wheels that PAs use when assigning associates to their work area and role for the day. The physical whiteboard is used along with laminated, magnetic badges that each correspond to a specific associate. These badges are placed on a specific and clearly marked section of the whiteboard, depending on the area and role assigned. In this worksheet's digital staffing board, the user simply inputs associates' logins instead.

**TotalsBoard**: This worksheet calculates and displays the number of associates staffed per department work area, as well as the department's total headcount.

**CleanTextSheet**: Like the name implies, this worksheet outputs the information entered on the two worksheets above in simple black-and-white text that's easy to read, save, and share.

**TextOutputFormulas**: This hidden worksheet is where a lot of the magic happens. It contains formulas that sanitize user input and that are used by CleanTextSheet to filter-out irrelevant text.


## Project Aim
- I started this project around September 2023, with the aim to 'git gud' at Excel.

I decided to start learning Excel in May 2023, after I bombed a pre-interview Excel/VBA assessment test that hit me by surprise. From May-September, I logged about 40 hours total, studying a little bit of everything. To this project, I dedicated about 50 hours, which means that in total I have less than 100 hours of Excel experience. Despite having limited experience, I was able to complete this unique and challenging project.

I know core Java really well, and a lot of the concepts, key words, and method names have analogues in Excel. I know that learning arrays, how to write complex functions, and how to automate tasks with VBA will come relatively easily given my programming background, which is why this project appealed to me; it focuses more on the visual/graphic design/UX side of Excel, which has no equivalent in Java. Merging cells, customizing their borders, aligning cell text, and giving columns/rows specific widths/heights are all skills that this project helped me learned well.

- Another aim of this project was to create a digital staffing tool for SAN3's Shipdock leadership to use in conjunction with the physical whiteboard. ***This workbook is not meant to replace, but rather to supplement the physical board.***

Initially, this project consisted of only 1 worksheet: MainBoard, the digital counterpart of the physical whiteboard-on-wheels.

However, after seeing the PAs calculate totals by hand, I decided to create and add a 2nd worksheet to the project. I named this worksheet TotalsBoard, and it automatically calculates and updates staffing numbers as PAs enter or delete associate logins.

Similarly, I noticed that the associates that help the PAs with staffing were typing roles and logins one-by-one, and then sending this information to other parties via messaging app. For example, they type: [Lanes 18-25: PG: brandon, WS: joseag, Supplies: estefania]. This is time-consuming and error-prone, which is why I decided to create and add a 3rd worksheet to the project. I named this worksheet CleanTextSheet, and it automatically gathers, cleans, and displays staffing information in a simple text format.


## Why it Matters
Shipdock staffing is an anomaly, a challenge.

The department has over 30 roles in which an associate can be staffed in. Other departments have only a fraction of this amount. Thus, assigning work areas and roles, and modifying these assignments throughout the course of a 10-hour shift is the Amazon equivalent of conducting an orchestra.

***This workbook has the potential to revolutionize the Shipdock staffing workflow***, the potential to help labor planners achieve a Bach-like performance. This workbook has the tools to assist PAs, the department's conductors, in producing a beautiful symphony of associate movement across dispersed work areas. This workbook helps PAs hit every single staffing note, for with this workbook they can easily reference, save and share important staffing information even when they are physically distant from the whiteboard.

This workbook makes it possible to update staffing roles based on business needs. When the physical board becomes outdated (due to roles being added and/or removed) or damaged to the point where it's no longer usable, I can use the skills that I gained while working on this project to create an updated template, and then suggest that the template be printed on a new, physical whiteboard.


## Technologies, Set-Up, and Configuration


## Program Instructions
**MainBoard**: Type in associate logins into select cells. My login is "joseag", so a PA would type "joseag" into, say, cell W26, which corresponds to the PG role for EAST AR BELOW MEZZ (aka "Flats" area) LANES 18-25.

In the GO-CART / NON-INVENTORY section:\
Enter a dock door number into the following cells: AO44:AO47.\
Enter a login into the following cells: AQ44:AQ47 and AS44:AS47 (GO-CART role).\
Enter a login into the following cells: AO48, AQ48, and AS48 (EYT role).



