==========================================================================================
(Group 31)              Faculty Data Visualization Script               ( IDC 409 Project)
==========================================================================================

Author: Abhinandan Angra (MS20042), Bhavya Sen (MS20131)
Date: November,2023
Group: 31


Repository link:
-----------------
https://github.com/abhinandanangra/IDC409---Web-Scraping-Project

Data Extracted from :
----------------------
1. https://math.iisc.ac.in/faculty.html
2. https://www.math.iitb.ac.in/People/faculty.php
3. https://www.bose.res.in/people/FacultyMembers.jsp


Description:
-------------
This notebook(s) extracts data from three webpages mentioned above and stores that data in a sqlite3 database named
`Faculty_list.db`. The database details are mentioned ahead.

Usage:
------
1. Install the necessary libraries if running on local runtime.
2. Google collab notebook was used to run this and is recommended as well.
3. The code blocks are explained using comments and notes in the notebook.

Files:
------
1. `faculty_visualizations.png`: Image file containing visualizations of the number of faculty per department.
2. `research_interests_wordcloud.png`: Image file containing a word cloud of research interests.
3. `phd_locations.png`: Image file containing visualizations of the most common PhD locations.
4. `idc409_group31_compiled.ipynb`: Interactive notebook containing web scraping code, database generation and visualization code.
5. `idc409_group31_dataVisualization.ipynb`: Interactive notebook containing code for visualization of data.

Note:
------
- An extra file for data visualization is made for precautinary measures, considering the websites might go down or have errors when the code is run.
  If that does happen one could upload the `Faculty_list.db` in the data visualization notebook runtime and run the code to generate the plots.
- Please clear the runtime, whenever database is changed.

Database:
---------
The script connects to an SQLite database named `Faculty_list.db` with the following tables:
- `faculty_combined_list`
- `Faculty_iitb_math`
- `faculty_iisc_math`
- `faculty_snbose`

For any questions or issues, please contact ms20042@iisermohali.ac.in & ms20131@iisermohali.ac.in.

=======================================================================================================
