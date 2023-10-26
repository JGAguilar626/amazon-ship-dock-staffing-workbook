<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/6bc1b670-8ad4-46ca-9cb5-18471c7ac556" width="640" height="400"></div>

# <div align="center">amazon-shipdock-staffing-workbook</div>
This project consists of a Microsoft Excel workbook that can be used by Amazon Fulfillment Shipdock department leadership to plan and visualize labor allocation.

## Project Description
This project consists of an Excel (.xlsx) workbook with 4 worksheets.

**MainBoard**: This worksheet is the digital version of a real-life whiteboard-on-wheels that PAs use when assigning associates to their work area and role for the day. The physical whiteboard is used along with laminated, magnetic badges that each correspond to a specific associate. These badges are placed on a specific and clearly marked section of the whiteboard, depending on the area and role assigned. In this worksheet's digital staffing board, the user simply inputs associates' logins instead.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/6bc1b670-8ad4-46ca-9cb5-18471c7ac556" width="640" height="400"></div>

-----

**TotalsBoard**: This worksheet calculates and displays the number of associates staffed per department work area, as well as the department's total headcount.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/6de0ca6a-4b25-41d0-9ee2-1c52ddcf2429" width="640" height="400"></div>

-----

**CleanTextSheet**: Like the name implies, this worksheet outputs the information entered on the two worksheets above in simple black-and-white text that's easy to read, save, and share.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/e2573906-18bf-4d98-b3f8-9852eeea1bf4" width="640" height="400"></div>

-----

**TextOutputFormulas**: This hidden worksheet is where a lot of the magic happens. It contains formulas that sanitize user input and that are used by CleanTextSheet to filter-out irrelevant text.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/7eb98bef-56c4-4983-b24c-6fd05ca1a508" width="640" height="400"></div>


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


## Program Instructions
**(1) MainBoard**: Type in associate logins into select cells. My login is "joseag", so a PA would type "joseag" into, say, cell W26, which corresponds to the PG role for EAST AR BELOW MEZZ (aka "Flats" area) LANES 18-25.

In the GO-CART / NON-INVENTORY section:\
Enter a number into the following cells: AO44:AO47 (DOCK DOOR NUMBER).\
Enter a login into the following cells: AQ44:AQ47 and AS44:AS47 (GO-CART role).\
Enter a login into the following cells: AO48, AQ48, and AS48 (EYT role).

Below is an example of what the section should look like.
<div align="left"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/1eb5c545-3a9b-45af-a335-3f3f78495d24" width="340" height="200"></div>

-----

**(2) TotalsBoard**: This worksheet contains the MANUAL-ADD BABY-BOARD (I had fun with the name). This baby provides staffing flexibility and customization. Simply type in the name of the role ***AND*** the corresponding login, and the workbook will automatically update the headcount for the area. Any roles and logins entered here will also be displayed in the worksheet CleanTextSheet. Note that if an user enters a role but not its corresponding login, the worksheet will not increase the total (and CleanTextSheet won't display it). Also, don't type a colon after the role name, for the worksheet CleanTextSheet automatically does this for you. Below is an example of how the BABY-BOARD should be filled out.

<div align="left"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/a58c5413-9510-422c-aa10-fc2852d8b77b" width="480" height="270"></div>

-----

**(3) CleanTextSheet**: Once you have completed worksheets MainBoard and TotalsBoard to your liking, navigate to the CleanTextSheet worksheet and:
- first, on the filter button located in cell A1
- second, check the box for (Select All)
- third, uncheck the box for the value 0 (located right under (Select All))
- fourth, scroll all the way down and uncheck the box for (Blanks)
- finally, click the OK button
You should now be able to see all the logins and their corresponding roles.

The image below shows how CleanTextSheet should output the data for the GO-CART / NON-INVENTORY group, assuming we input the same data as the image in one of our previous examples.
<div align="left"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/bf5a8c94-bd33-48a9-8b8c-2a7215f203c0" width="274" height="300"</div>


## Features
- I made stylistic improvements to the main board's layout. For example, I improved the WEST AR BELOW MEZZ and EAST AR BELOW MEZZ sections of the board by clearly separating the aisles into 4 groups.
- The physical board has a dead area, a column of blank cells, on its right edge. I turned this dead zone into a VTO zone.
- I added a Notes section to the worksheet MainBoard. The note-taking area sits directly to the right of the digital board, facilitating the writing of memos and other important staffing information.
- Added the current time (using =NOW()) to the left side of the digital board. Also on top of the Notes section.
- 









