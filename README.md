<h1> ANALYSIS ON STUDENTS DATA </h1>

**Data Sources**:

<table border="0" cellpadding="0" cellspacing="0" width="1518" style="">
  <thead>
    <tr height="23" style="height: 17pt;">
      <th>Document Name</th>
      <th>Details</th>
      <th>Reference Link</th>
    </tr>
  </thead><colgroup><col width="272" style="width: 204pt;"><col width="687" style="width: 515pt;"><col width="559" style="width: 419pt;"></colgroup>
  <tbody>
    <tr height="47" style="height: 35pt;">
      <td height="47" class="xl68" style="padding-top: 1px; padding-right: 1px; padding-left: 1px; font-size: 11pt; font-family: Calibri, sans-serif; vertical-align: middle; border-width: medium 1pt 1pt; border-style: none solid solid; border-color: currentcolor windowtext windowtext; border-image: none; white-space: nowrap; text-align: center; height: 35pt;">Table_Insert.xlsx</td>
      <td class="xl69" width="687" style="padding-top: 1px; padding-right: 1px; padding-left: 1px; font-size: 11pt; font-family: Calibri, sans-serif; vertical-align: middle; border-width: medium 1pt 1pt medium; border-style: none solid solid none; border-color: currentcolor windowtext windowtext currentcolor; border-image: none; width: 515pt;">This file contains the table insertion records that are used as part of this analysis</td>
      <td class="xl77" width="559" style="padding-top: 1px; padding-right: 1px; padding-left: 1px; color: rgb(70, 120, 134); font-size: 12pt; text-decoration: underline; font-family: &quot;Aptos Narrow&quot;, sans-serif; vertical-align: middle; border-width: medium 1pt 1pt medium; border-style: none solid solid none; border-color: currentcolor windowtext windowtext currentcolor; border-image: none; text-align: center; width: 419pt;"><a href="https://docs.google.com/spreadsheets/d/1pPImczkzRj0G5s9R6DG21kSI8kduFU-H/edit?usp=sharing&amp;ouid=114840663789662506255&amp;rtpof=true&amp;sd=true"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPrK-y05cfo5GM1Pg55QJLLirq54AByCaozg&s" width="50" height="30"/></a></td>
    </tr>
    <tr height="21" style="height: 16pt;">
      <td rowspan="3" height="65" class="xl71" style="padding-top: 1px; padding-right: 1px; padding-left: 1px; font-size: 11pt; font-family: Calibri, sans-serif; vertical-align: middle; border-width: medium 1pt 1pt; border-style: none solid solid; border-color: currentcolor windowtext black; border-image: none; white-space: nowrap; text-align: center; height: 49pt;">Students_Data.xlsx</td>
      <td rowspan="3" class="xl72" width="687" style="padding-top: 1px; padding-right: 1px; padding-left: 1px; font-size: 11pt; font-family: Calibri, sans-serif; vertical-align: middle; border-width: medium 1pt 1pt; border-style: none solid solid; border-color: currentcolor windowtext black; border-image: none; width: 515pt;">This file contains the source records that are used as part of this analysis</td>
      <td rowspan="3" class="xl78" width="559" style="padding-top: 1px; padding-right: 1px; padding-left: 1px; color: rgb(70, 120, 134); font-size: 12pt; text-decoration: underline; font-family: &quot;Aptos Narrow&quot;, sans-serif; vertical-align: middle; border-width: medium 1pt 1pt; border-style: none solid solid; border-color: currentcolor windowtext black; border-image: none; text-align: center; width: 419pt;"><a href="https://docs.google.com/spreadsheets/d/1RxPu2aHZuMtDn5N9XbiYCZLU1yTa9KI3/edit?usp=sharing&amp;ouid=114840663789662506255&amp;rtpof=true&amp;sd=true"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPrK-y05cfo5GM1Pg55QJLLirq54AByCaozg&s" width="50" height="30"/></a></td>
    </tr>
    <tr height="21" style="height: 16pt;">
    </tr>
    <tr height="23" style="height: 17pt;">
    </tr>
    <tr height="24" style="height: 18pt;">
      <td height="24" class="xl68" style="padding-top: 1px; padding-right: 1px; padding-left: 1px; font-size: 11pt; font-family: Calibri, sans-serif; vertical-align: middle; border-width: medium 1pt 1pt; border-style: none solid solid; border-color: currentcolor windowtext windowtext; border-image: none; white-space: nowrap; text-align: center; height: 18pt;">Normalization</td>
      <td class="xl69" width="687" style="padding-top: 1px; padding-right: 1px; padding-left: 1px; font-size: 11pt; font-family: Calibri, sans-serif; vertical-align: middle; border-width: medium 1pt 1pt medium; border-style: none solid solid none; border-color: currentcolor windowtext windowtext currentcolor; border-image: none; width: 515pt;">This contains the Entity relationship Diagram</td>
      <td class="xl77" width="559" style="padding-top: 1px; padding-right: 1px; padding-left: 1px; color: rgb(70, 120, 134); font-size: 12pt; text-decoration: underline; font-family: &quot;Aptos Narrow&quot;, sans-serif; vertical-align: middle; border-width: medium 1pt 1pt medium; border-style: none solid solid none; border-color: currentcolor windowtext windowtext currentcolor; border-image: none; text-align: center; width: 419pt;"><a href="https://drawsql.app/teams/de-28/diagrams/de"><img src="https://deals.micro-saas.co/wp-content/uploads/2021/09/DrawSQL-FS-AFFI3-1076.png" width="45" height="60"/></a></td>
    </tr>
  </tbody>
</table>

Given source data has been analyzed and below mapping sheet has been
created for the same.

**Under Modified_Source_Data sheet, below modifications has been
performed:**

-   **Given column names has been modified in such a way to insert the
    column in the table [(Refer Table_Att Sheet in Students_data.xlsx
    Workbook)]{.mark}**

-   **Yellow highlighted cells values were added additionally to prevent
    null values in the primary value attributes**

-   **Separate tables has been created based on the data provided
    ([Refer Tables Sheet in Students_data.xlsx Workbook]{.mark})**

-   **Table column related attributes are placed under [Table_Att Sheet
    in Students_data.xlsx Workbook]{.mark}**

**[Create an ERD Diagram:]{.underline}**

![A screenshot of a computer Description automatically
generated](./media/image1.png){width="6.268055555555556in"
height="3.203472222222222in"}

**[Normalize the Data:]{.underline}**

-   To reduce complexity,

    -   Address related attributes ( student_addr and faculty_addr ) are
        not normalized further to each individual units

    -   project_supervisor_id and grade_points attributes are filled
        with random values so that new additional unique column has not
        been created to identify the record uniquely

-   Normalization has been performed under ["Normalization" sheet **in
    Students_data.xlsx Workbook**]{.mark}

    -   1 NF:

        -   Each cell to be single valued

        -   Entries in the column are same type ( Considering
            "Incomplete", "Withdrawn" has valid values under
            course_status column to uniquely identify it )

        -   All the primary key attributes are uniquely identifiable (
            project_supervisor_id and grade_points attributes are
            prefilled )

        -   **[Refer 1NF Heading under Normalization Sheet in
            Students_data.xlsx]{.mark}**

    -   2 NF:

        -   Removing non-key columns dependent on key

        -   **[Refer 2NF Heading under Normalization Sheet in
            Students_data.xlsx]{.mark}**

    -   3 NF:

        -   All fields can be determined only by key in the table not by
            any any other column.

        -   **[Refer 3NF Heading under Normalization Sheet in
            Students_data.xlsx]{.mark}**

[**Database Setup -- SQL Queries**:]{.underline}

**[1) Creation of Tablespace:]{.underline}**

CREATE TABLESPACE DATA_EGG

DATAFILE \'/opt/oracle/oradata/dataegg/dataegg.dbf\'

SIZE 500M

AUTOEXTEND ON

NEXT 10M MAXSIZE UNLIMITED;

![A screenshot of a computer program Description automatically
generated](./media/image2.png){width="2.748266622922135in"
height="1.3450349956255467in"}

**[2) Creation of a New User in the Newly Created Tablespace and
Assignment of Roles]{.underline}**

CREATE USER \"sqlmini\" IDENTIFIED BY \"sqlmini\"

DEFAULT TABLESPACE \"DATA_EGG\"

TEMPORARY TABLESPACE \"TEMP\";

GRANT \"SELECT_CATALOG_ROLE\" TO \"sqlmini\" ;

GRANT \"CONNECT\" TO \"sqlmini\" ;

ALTER USER \"sqlmini\" DEFAULT ROLE \"SELECT_CATALOG_ROLE\",\"CONNECT\";

GRANT SELECT ANY TABLE TO \"sqlmini\" ;

GRANT DELETE ANY TABLE TO \"sqlmini\" ;

GRANT DROP ANY TABLE TO \"sqlmini\" ;

GRANT UPDATE ANY TABLE TO \"sqlmini\" ;

GRANT ALTER ANY TYPE TO \"sqlmini\" ;

GRANT CREATE ANY TABLE TO \"sqlmini\" ;

![A screenshot of a computer program Description automatically
generated](./media/image3.png){width="2.901062992125984in"
height="2.1900995188101486in"} ![A screenshot of a computer Description
automatically
generated](./media/image4.png){width="2.8954746281714785in"
height="2.18588145231846in"}

**[3) Creation of Tables:]{.underline}**

**Student Table:**

![A screenshot of a computer program Description automatically
generated](./media/image5.png){width="1.9781419510061242in"
height="1.5945680227471566in"}

**Department table:**

![A screenshot of a computer program Description automatically
generated](./media/image6.png){width="1.9992268153980752in"
height="1.6115649606299212in"}

**Faculty table:**

![A screenshot of a computer Description automatically
generated](./media/image7.png){width="1.9258278652668417in"
height="1.704225721784777in"}

**Project_Advisor table:**

![A screenshot of a computer program Description automatically
generated](./media/image8.png){width="1.8009897200349956in"
height="1.3791360454943131in"}

**Project Table:**

![A screenshot of a computer program Description automatically
generated](./media/image9.png){width="2.1500306211723537in"
height="1.424938757655293in"}

**Student Project Table:**

![A screenshot of a computer Description automatically
generated](./media/image10.png){width="1.865479002624672in"
height="1.5709284776902888in"}

**Course Table:**

![A screenshot of a computer program Description automatically
generated](./media/image11.png){width="1.8049496937882765in"
height="1.3863320209973753in"}

**Student_Course Table:**

![A screenshot of a computer Description automatically
generated](./media/image12.png){width="2.1347944006999127in"
height="2.2737784339457567in"}

**Department_Course Table:**

![A screenshot of a computer Description automatically
generated](./media/image13.png){width="1.8603379265091864in"
height="1.5268810148731409in"}

**Provide access User to access Tablespace:**

![A computer screen shot of a message Description automatically
generated](./media/image14.png){width="2.9272681539807524in"
height="0.9041185476815398in"}

**[4) Insertion of Data to Tables:]{.underline}**

Import Data via SQL Developer for each tables with the respective sheets
from the "Table_Insert.xlsx" Workbook.

**Import Successful:**

![A screenshot of a computer Description automatically
generated](./media/image15.png){width="2.096129702537183in"
height="0.7505314960629921in"}

**[Practical Scenarios and SQL Queries:]{.underline}**

1\) In which courses, students under dept_id as 1 has failed?

![A screenshot of a computer program Description automatically
generated](./media/image16.png){width="3.5101279527559055in"
height="1.5890080927384076in"}

2\) Find Student details who are under Probation

![A screenshot of a computer Description automatically
generated](./media/image17.png){width="3.1655522747156604in"
height="1.3492016622922134in"}

3\) Provide project title, start and end date about Student "2020002"?

![A screenshot of a computer program Description automatically
generated](./media/image18.png){width="4.763030402449694in"
height="1.4247933070866141in"}

4\) How many students are studying in 1st semester?

![A screenshot of a computer program Description automatically
generated](./media/image19.png){width="2.2011778215223097in"
height="1.319248687664042in"}

5\) Give me student name with course name where they passed in
Distinction

![A screenshot of a computer Description automatically
generated](./media/image20.png){width="2.7633388013998252in"
height="1.6835367454068242in"}
