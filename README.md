# School District Analysis

## Overview of School District Analysis

The Chief Data Scientist of a city School District, Maria has been tasked with preparing data from the students' standardized test scores.  This data will be used for analysis; which includes reporting and presenting to each school and district levels.  This information will initiate informed discussions and strategic decisions about the proficiency of city schools testing.  
Maria has asked us for assistance in analyzing the data further to analyze student funding and student standardized test scores.  We have aggregated the data and showcased trends in school performance based on categories which will help the school board and superintendants make decision regarding school budgets and alocations.

After compiling data from 2 sources, we obtained:
  
  *1.  District Summary - provides a snapshot of the districts' key metrics*
  
  *2.  Per School Summary - provides key metrics for each school*
  
  *3.  A table presenting the top 5 and bottom 5 performing schools based on overall students passing*
  
  *4.  Average math and reading scores in each grade, each school*
  
  *5.  School performance based on budget per student*
  
  *6.  School performance based on school size*
  
  *7.  School performance based on school type*
  

After the original analysis was stated above, we were advised that there was a discrepency on the math and reading scores for the 9th grade students attending the Thomas High School.  The results noted below are based on the revised outcome.

### Resources used:
[schools_complete.csv](https://github.com/JediMasterSlagle/School_District_Analysis/blob/main/schools_complete.csv)

[students_complete.csv](https://github.com/JediMasterSlagle/School_District_Analysis/blob/main/students_complete.csv)

[clean_students_complete.csv](https://github.com/JediMasterSlagle/School_District_Analysis/blob/main/clean_students_complete.csv)


## School Analysis Results
Firstly we removed all the scores for grade 9 students for Thomas High School which was a total of 461 students.  The following are the effects of the new analysis.
  
  *1. Below are the screenshots of the District summary - providing a snapshot of the total population, budget, average scores and passing rates for the entire district.  The 9th grade from Thomas High amounted to 1.17% of the total student population.
  
  
  *Original District sum
  
  [Original summary](https://github.com/JediMasterSlagle/School_District_Analysis/blob/main/school%20sum%20df.png)
  
  *Revised summary
  
  [Revised Summary](https://github.com/JediMasterSlagle/School_District_Analysis/blob/main/school%20sum%20without%209th.png)
  
  
  *2.  There are a total of 1635 students at Thomas High.  73% are from grade 10th to 12th.  Once we eliminated the grade 9 scores, the percentage of students passing each subject or both together dropped by an average of 26%, since the calculation was still taking the total number students into account.
  
  *3.  After the revised analysis with the 9th grade scores replaced the overall passing percentage for the school was at 65%, it would have placed Thomas High School within the bottom 10 schools, placing them at the 8th position.  However once the scores were replaced and taking the grade 9's out of the equation, the school falls within the top 5 performers, placed 2nd on the list as the original analysis.  
  
  *Top 5 schools
  [Top 5](https://github.com/JediMasterSlagle/School_District_Analysis/blob/main/top%205%20schools.png)
  


## School District Analysis Summary

Overall the discrepency of the scores impacted the entire analysis.  The revised analysis would not be a true statement as we are not calculating the actual true student population for this district.  Though the student count of 461 from 9th grade attending Thomas High is minimal compared to a total of 39,170 students; their true scores may still impact the results positively or negatively.  

  1. The performance for Thomas High individually situates them at the second place in the top 5 schools list.  This may change if we had the actual results from the 9th grade.  The results may put them in the bottom producing schools.

  2. The performance results on each grade level may be impacted as well.  Currently the results have the 9th grade per school performing at the same rate.  Actual results may show Thomas High's 9th grade performing better or worse than the other schools.
  
 3. Based on the performance the budget per student may change as well which will impact the decision for the school boards funding allocation.  The true results may change the averages and the passing percentages, placing them in the next higher or lower bin of spending.
  
  4. if the averages for grade 9 are low, this may bring down the overall passing rate down for the school resulting in change of the School Type summary.  We may see District schools out performing the Charter schools.
  
