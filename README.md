# Pewlett-Hackard-Analysis

## Overview
The purpose of this analysis was to provide executives at Pewlett-Hackard (PH) with information about the company's projected retirements over the coming years. The tables under analysis consist of basic employee information ranging from demographics, past and current job titles, hiring and termination dates (if applicable). The analysis of the employee data tables will potentially reduce the labor-loss impact of baby-boomers born 1952-1955 that are nearing retirement age so executives and managers can examine who from the organization should participate in mentorship for knowledge and skill transfer.

In addition to the code provided in SQL, the deliverables included the following set of data files:

## Results
Below is a set of 4 key findings from the analysis described above.

1. **Prioritizing senior engineers and staff**: A significant number of senior engineers are predicted to retire soon. This presents a serious threat to a company as dependent on its technical workforce as PH. Therefore, the most pressing need in terms of recruitment of new employees may be engineering talent.
2. **Senior staff exodus**: Relatedly, a wave of retirements from senior staff in general (including those with the title of senior staff and senior engineers) will create a large dropoff in institutional knowledge and company-specific expertise across functional areas and departments. This broadens the first point, made above.
3. **Observing potential mentors**: With the help of an Excel pivot table, I was able to discern the two bullet points below. These findings provide some insight into the number of potential mentors. Given the volume of PH's workforce, there seem to be relatively few mentors to go around.
   * There are about 1500 employees eligible to be mentors
   * A majority (about 730) are either senior staff or senior engineers

![alt text](

4. **Targeting mentors strategically**: In terms of who to target as potential mentors, executive staff may want to consider employee hire date as a variable of interest. This would enable them to focus on staff that have been on board during key moments in the company's history. If executives would prefer for mentored staff to benefit from maximum institutional knowledge, then it would be appropriate to target onboarding date ranges that reach as far back as possible. Conversely, if there are past events or processes that the company would prefer to leave behind, they may target retiring employees whose onboarding date is more recent. It's important to acknowledge that some of these employees may have been with the company prior, but underwent a title change more recently.

## Summary
Two essential questions about the direction forward were posed at the beginning of the analysis. Note responses below.

1. **How many roles will need to be filled?** The "Retiring_titles" data document exhibits a breakdown of retirements by role. The total number of roles to be filled is 90,398 - a large figure, indeed. An additional query completed for retirements by department may also be useful as executives determine their talent strategy moving forward. Note the image of this query below.

![alt text](

3. **Are there enough qualified, retirement-ready employees in the departments to mentor the next gen of PH employees?** Note the comparison between retiring employees by title and current employees by title below.

![alt text](

As you can see, there is a significant disparity between total current employees (most of whom will not be retiring) and eligible mentors. In all likelihood, there will not be enough qualified, retirement-ready employees (especially in the larger departments) to mentor the next generation of employees. Executive staff may want to look into external opportunities (i.e. through externships) as a means for creating the abundance of mentoring relationships that the company may need in the coming years.
