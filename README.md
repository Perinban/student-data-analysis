# Student Database Design

This project takes a denormalized student dataset and redesigns it as a structured relational database. The work focuses on identifying entities and relationships, defining keys, normalizing the data through 1NF/2NF/3NF, creating the ER model, and preparing Oracle SQL/database records from the transformed structure.

## What the project does

1. Review the source student dataset and map the available attributes.
2. Identify logical entities such as students, faculty, courses, projects, and related records.
3. Define primary keys and foreign-key relationships.
4. Normalize the source structure through first, second, and third normal form.
5. Create the entity-relationship model for the normalized design.
6. Prepare the Oracle tablespace/user/table setup used by the project.
7. Prepare table-insert records from the transformed source data.

## Project resources

These are the original workbooks and ER diagram linked from the project report.

| Resource | Description | Link |
| --- | --- | --- |
| `Students_Data.xlsx` | Source records, mapping details, and normalization worksheets used to design the relational model. | [Open workbook](https://docs.google.com/spreadsheets/d/1RxPu2aHZuMtDn5N9XbiYCZLU1yTa9KI3/edit?usp=sharing&ouid=114840663789662506255&rtpof=true&sd=true) |
| `Table_Insert.xlsx` | Prepared records used for loading data into the normalized database tables. | [Open workbook](https://docs.google.com/spreadsheets/d/1pPImczkzRj0G5s9R6DG21kSI8kduFU-H/edit?usp=sharing&ouid=114840663789662506255&rtpof=true&sd=true) |
| Entity Relationship Diagram | DrawSQL model showing the normalized entities and relationships. | [Open DrawSQL diagram](https://drawsql.app/teams/de-28/diagrams/de) |

## Normalization approach

The project documents the transformation through:

- **1NF** — atomic values and consistently structured rows/columns;
- **2NF** — removal of partial dependencies on composite keys; and
- **3NF** — removal of transitive dependencies so non-key fields depend on the table key.

The normalized design separates repeated student, faculty, course, and project information into related tables rather than keeping all attributes in one source structure.

## Technologies

- Oracle SQL
- Relational data modeling
- Database normalization
- DrawSQL
- Spreadsheet-based source mapping and load preparation

## Repository contents

```text
.
├── media/       # ERD, SQL, and database-setup screenshots from the project report
└── README.md
```

The project resources above contain the source data, normalization/mapping work, table-insert records, and ER model used to produce the final database design.
