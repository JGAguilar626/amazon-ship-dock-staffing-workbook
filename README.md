<div align="center"><img src="https://github.com/JGAguilar626/amazon-ship-dock-staffing-workbook/assets/129235347/ba332fd3-22b8-41cd-8ed7-489cc3eb0267" width="640" height="400"></div>

# <div align="center">amazon-ship-dock-staffing-workbook</div>
This project consists of a Microsoft Excel workbook that can be used by Amazon Fulfillment Ship Dock department leadership to plan and visualize labor allocation.

## Project Description
This project consists of an Excel (.xlsx) workbook with 5 worksheets.

**MainBoard**: This worksheet is the digital version of a real-life whiteboard-on-wheels that PAs use when assigning associates to their work area and role for the day. The physical whiteboard is used along with laminated, magnetic badges that each correspond to a specific associate. These badges are placed on a specific and clearly marked section of the whiteboard, depending on the area and role assigned. In this worksheet, the user simply inputs associates' logins instead.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-ship-dock-staffing-workbook/assets/129235347/ba332fd3-22b8-41cd-8ed7-489cc3eb0267" width="640" height="400"></div>

-----

**ManualAddBoard**: This worksheet provides department labor planners the space for an additional 244 customized roles and logins. Included in these 244 extra slots are 64 VTO slots.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-ship-dock-staffing-workbook/assets/129235347/683e149e-efdf-494d-8dfc-9a4a839d6575" width="640" height="400"></div>

-----

**TotalsBoard**: This worksheet calculates and displays the number of associates staffed per department work area, as well as the department's total headcount.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-ship-dock-staffing-workbook/assets/129235347/547147a0-a049-4669-a659-76525907e89e" width="640" height="400"></div>

-----

**CleanTextSheet**: Like the name implies, this worksheet outputs the information on the two worksheets above in simple black-and-white text that's easy to read, save, and share.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-ship-dock-staffing-workbook/assets/129235347/b51aef79-0d6a-48e0-9480-0bcafad1ca34" width="640" height="400"></div>

-----

**TextOutputFormulas**: This hidden worksheet is where a lot of the magic happens. It contains formulas that sanitize user input and that are used by CleanTextSheet to filter-out irrelevant text.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-ship-dock-staffing-workbook/assets/129235347/e79b9e83-e0f1-46e3-a439-6466059096ae" width="640" height="400"></div>

## Project Aim
- Help me git gud at Excel.

I decided to start learning Excel in May 2023, after I bombed a pre-interview Excel/VBA assessment test that hit me by surprise. From May-September, I logged about 50 hours total, studying a little bit of everything. To this project, I have dedicated about 75-100 hours, which means that in total, I have about 150 hours of Excel experience. Nonetheless, I was able to complete this unique and challenging project.

- Help me learn the visual/graphic design/UX side of Excel.

I know core Java really well, and a lot of the concepts, key words, and method names have analogues in Excel. I know that learning arrays, how to write complex functions, and how to automate tasks with VBA will come relatively easy given my programming background, which is why this project appealed to me; it focuses more on the visual/graphic design/UX side of Excel, which has no equivalent in Java. Merging cells, customizing their borders, aligning cell text, and giving columns/rows specific widths/heights are all skills that this project helped me learned well.

- Create a digital staffing tool for SAN3's Ship Dock leadership to use in conjunction with, ***or as a replacement for,*** the physical whiteboard.

Initially, this project consisted of only 1 worksheet: MainBoard, the digital counterpart of the physical whiteboard-on-wheels. However, after seeing the PAs calculate totals by hand, I decided to create and add a 2nd worksheet to the project. I named this worksheet TotalsBoard, and it automatically calculates and updates staffing numbers as PAs enter or delete associate logins. I also noticed that the associates that help the PAs with staffing were typing roles and logins one-by-one, and then sending this information to other parties via messaging app. For example, they type: [Lanes 18-25: PG: brandon, WS: joseag, Supplies: estefania] [Spirals: PG: Jose]. This is time-consuming and error-prone, which is why I decided to create and add a 3rd worksheet to the project. I named this worksheet CleanTextSheet, and it automatically gathers, cleans, and displays staffing information in a simple text format.


## Why it Matters
Amazon Ship Dock staffing is an anomaly, a challenge.

The department has over 30 roles in which an associate can be staffed in. Other departments have only a fraction of this amount. Thus, assigning work areas and roles, and modifying these assignments throughout the course of a 10-hour shift is the Amazon equivalent of conducting an orchestra.

***This workbook has the potential to revolutionize the Ship Dock staffing workflow***, the potential to help labor planners achieve a Bach-like performance. This workbook has the tools to assist PAs, the department's conductors, in producing a beautiful symphony of associate movement across dispersed work areas. This workbook helps PAs hit every single staffing note, for with this workbook they can easily reference, save and share important staffing information even when they are physically distant from the whiteboard.

This workbook makes it possible to update staffing roles based on business needs. When the physical board becomes outdated (due to roles being added and/or removed) or damaged to the point where it's no longer usable, I can use the skills that I gained while working on this project to create an updated template, and then suggest that the template be printed on a new, physical whiteboard.


## Program Instructions
**(1) MainBoard**: Type in associate logins into select cells. My login is "joseag", so a PA would type "joseag" into, say, cell W26, which corresponds to the PG role for EAST AR BELOW MEZZ (aka "Flats" area) LANES 18-25.

In the GO-CART / NON-INVENTORY section:\
Enter a number into the following cells: AO42:AO45 (DOCK DOOR NUMBER).\
Enter a login into the following cells: AQ42:AQ45 and AS42:AS45 (GO-CART role).\
Enter a login into the following cells: AO46, AQ46, and AS46 (EYT role).

Below is an example of what the section should look like.
<div align="left"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/1eb5c545-3a9b-45af-a335-3f3f78495d24" width="340" height="200"></div>

-----

**(3) CleanTextSheet**: Once you have completed worksheets MainBoard and TotalsBoard to your liking, navigate to the CleanTextSheet worksheet and:
- first, click on the filter button located in cell A27
- second, check the box for (Select All)
- third, scroll all the way down and uncheck the box for (Blanks)
- fourth, click the OK button

You should now be able to see all the logins and their corresponding roles.

The image below shows how CleanTextSheet should output the data for the GO-CART / NON-INVENTORY group, assuming we input the same data as the image in one of our previous examples.
<div align="left"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/bf5a8c94-bd33-48a9-8b8c-2a7215f203c0" width="274" height="300"></div>


## Features
- I made stylistic improvements to the main board's layout. For example, I improved the WEST AR BELOW MEZZ and EAST AR BELOW MEZZ sections of the board by clearly separating the aisles into 4 groups. See Exhibit 1 below.
- The physical board has a dead area, a column of blank cells, on its right edge. I turned this dead zone into a VTO zone (everybody secretely wishes they were staffed here all day, every day). See Exhibit 2 below.
- Added the current time (using =NOW()) to the left side of the digital board. Also on top of the Notes section.
- In the worksheet TotalsBoard, users can see the total number of associates per work area and per area subgroup. For example, an user can see that EAST AR BELOW MEZZ LANES 18-25 has a total of, say, 3 associates staffed and that they are staffed as follows: 1 in the PG role, 1 in the Waterspider role, and 1 in the Supplies role.
- The worksheet ManualAddBoard features the great MANUAL-ADD BOARD, into which planners can input roles that are not accounted for in the MainBoard worksheet.
- The worksheet TotalsBoard features a chart(?)(Is this the best name for it?) that adds-up the total headcount accross all work areas and displays it in a "you-can't-miss-it-if-you-wanted-to" highlighter-yellow colored cell.
- This workbook makes use of the almighty =TRIM() function to sanitize user input, preventing false-positives by eliminating useless whitespace.
- I spent many hours merging and locking cells, which should help maintain worksheet integrity and data accuracy.

-----

***Exhibit 1***:
I improved the WEST AR BELOW MEZZ and EAST AR BELOW MEZZ SECTIONS.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/e3720083-1924-4daf-bdf8-1c1fef5b6336" width="500" height="281"></div>

-----

***Exhibit 2***:
Converted what appears to be a dead zone into a VTO (Party) zone.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/f5fa8cc4-7f54-42aa-9f61-e2399dcde6a4" width="500" height="281"></div>


## Misc.
Below is a photograph of the real-life Shipdock staffing board.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/1f4b8a09-23f3-4784-938e-6d7062c7cfec" width="500" height="281"></div>

-----

Below is a photograph of my magnet.

<div align="center"><img src="https://github.com/JGAguilar626/amazon-shipdock-staffing-workbook/assets/129235347/f9f87deb-e70e-4e48-b500-c9abdcb7f3bf" width="200" height="350"></div>
