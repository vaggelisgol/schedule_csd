# schedule_csd
Forked from https://github.com/giorgosioak/schedule_csd

You can view the schedule at: https://johnnykaz.github.io/schedule_csd/

Preview of the website:

<img src="resources/pick_classes.gif" alt="preview of the website" style="zoom:50%;" />


## Contribute
The schedule is located at: js/data.js



#### Updating the website for a new semester

To update the contents of the website for a new semester, you need to modify the following:

- update the schedule (located at `js/data.js`) with the new classes, but keep the same format.

  You can use the scripts (located at `extract_scripts/`) to help you extract the schedule in the correct format from the official pdf schedule published in the [csd website](https://www.csd.uoc.gr/CSD/index.jsp?content=akadimaiko_hmerologio&openmenu=demoAcc6&lang=gr). The scripts may not work perfectly, so some manual work may still be needed. 

- update the title (located at `index.html`) to reflect the new semester 

  (e.g. `ΕΑΡΙΝΟ ΕΞΑΜΗΝΟ 2023` $\to$ `ΧΕΙΜΕΡΙΝΟ ΕΞΑΜΗΝΟ 2023-2024`)

- update the variable `CALENDAR_END_DATE` (located at `index.html`) to the semester's last date of classes.



## Report a bug or request a feature:

Open a new [issue](https://github.com/JohnnyKaz/schedule_csd/issues) if there isn't already