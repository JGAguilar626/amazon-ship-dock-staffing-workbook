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

I know core Java really well, and a lot of the concepts, key words, and method names have analogues in Excel. I know that learning arrays, how to write complex functions, and how to automate tasks with VBA will come relatively easily given my programming background, which is why this project appealed to me; it focuses more on the visual/graphic design/UX side of Excel, which has no equivalent in Java. Merging cells, customizing their borders, aligning cell text, and giving columns/rows specific widths/heights are all things that have no equivalent in Java, and that this project allowed me to learn well.

- Another aim of this project was to create a digital staffing tool for SAN3's Shipdock leadership to use in conjunction with the physical whiteboard. ***This workbook is not meant to replace, but rather to supplement the physical board.***

Initially, this project consisted of only 1 worksheet: MainBoard, the digital counterpart of the physical whiteboard-on-wheels. However, after seeing the PAs calculate totals by hand, I decided to create and add a 2nd worksheet to the project. I named this worksheet TotalsBoard, and it automatically calculates and updates staffing numbers as PAs enter or delete associate logins. Similarly, I noticed that the associates taht help the PAs with staffing were typign roles and logins one-by-one, and then sending this information to other parties via messaging app. For example, they type: [Lanes 18-25 Waterspider: joseag, brandon, estefania]. This is time-consuming and error-prone. Thus I decided to create and add CleanTextSheet to the workbook, which automatically gathers, cleans, and displays staffing information in a simple text foromat.

## Why it Matters
Shipdock staffing is an anomaly when compared to other departments. The reason being is that Shipdock contains over 30 roles in which an associate can be staffed in. Other departments have only a fraction of this amount. Thus, assigning work areas and roles, and modifying these assignments throughout the course of a 10-hour shift is the Amazon equivalent of conducting an orchestra. This workbook has the potential to revolutionize the Shipdock staffing workflow. This workbook has the tools to assist PAs, the department's conductors, in producing a beautiful symphony of associate movement across dispersed work areas. This workbook helps PAs hit every single staffing note, for with this workbook they can easily reference, save and share important staffing information when they are physically far away from the whiteboard. With this workbook, PAs can save time and energy, for this workbook automatically calculates and updates staffing numbers. With this workbook, PAs can quickly read, copy/paste, save and share staffing information in simple black-and-white text format.

Things constantly change at Amazon, and another benefit that this workbook provides is the ability to modify and update staffing roles based on business needs. If the physical board becomes outdated or damaged to the point where its no longer usable, I can use the knowledge and experience that I gained from this project to quickly create an updated board within the workbook, and then suggest that the digital board be printed on a new, physical whiteboard.

## Technologies, Set-Up, and Configuration


## Program Instructions
**MainBoard**: Type in associate logins into select cells. My login is "joseag", so a PA would type "joseag" into, say, cell W26, which corresponds to the PG role for the EAST AR BELOW MEZZ (aka "Flats" area) LANES 18-25.

Within thet GO-CART / NON-INVENTORY section, type in a dock door number into any or all of the following cells: AO44:AO47. The following cells are meant for logins: AQ44:AQ47 and AS44:AS47. Cells AO48, AQ48, and AS48 are meant for logins as well, for associates placed in the EYT role.



