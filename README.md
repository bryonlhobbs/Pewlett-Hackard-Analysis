# Pewlett-Hackard-Analysis

## Overview
For this analysis, I was asked to determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program. This is because hte manager wants to prepare for the "Silver Tsunami", a mass exodus of employees retiring.

## Results

  -   The first thing that stands out is the total number of employees retiring.  There are 72,458 employees who are ready for retirement, which means that there will be a lot of job openings very shortly.

  -   The second item of note is that many of the upcoming retirees were seniors in their roles.  This means that some non-senior employees should be in line for promotions.  This can be seen in the retiring_titles.csv.

<img width="227" alt="Retiring_Titles_csv" src="https://user-images.githubusercontent.com/99457275/163463492-5c06a508-1a0b-46b3-b6d1-4133f21b6474.png">

  -   This brings me to my third observation.  There are 1549 employees in the mentorship_eligibility.csv.  Even if management convinces every eligible mentor to commit to mentoring, there is a drastic shortage of mentors, assuming a one-to-one arrangement.

  -   The fourth observation is that we were asked to call the first instance of an eligible mentor, which led to some rows of the table showing an outdated job title.  We should have called the most recent job title so that the mentorship program can be most efficiently utilized by asking mentors to coach new employees at the mentor's current level.

## Summary
1. There are 72,458 employees who are ready for retirement, which means that there will be a lot of job openings very shortly.  This can be determined through the following query and result: 

<img width="465" alt="Retiring_Employees_Count" src="https://user-images.githubusercontent.com/99457275/163465260-58ae3019-9f4a-4e89-b230-06c3325ba1cf.png">

2. I would say that there are not enough mentors, and in order to determine this, I would find the count of eligible mentors and compare it to the number of retirement eligible employees from the last question, as that is equal to the number of upcoming job openings.  Below is the screenshot of mentor count:

<img width="617" alt="Mentor_Count" src="https://user-images.githubusercontent.com/99457275/163465848-df0563e5-ccb6-46ce-bde8-9e5580fb287a.png">


