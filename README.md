# Module_4

**Background**

The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

**This new assignment consists of two technical analysis deliverables and a written report to present your results.**

  - Deliverable 1: Replace ninth-grade reading and math scores
  - Deliverable 2: Repeat the school district analysis
  - Deliverable 3: A written report for the school district analysis (README.md)

  ## Deliverable 1: Replace ninth-grade reading and math scores
  Use the Pandas NumPy module to change the reading and math scores to NaN for ninth-grade reading and math scores for Thomas High School
  
  ## Deliverable 2: Repeat the school district analysis
  
Repeat the school district analysis you did in this module, and recreate the following metrics:

- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type
  
 ## Deliverable 3: A written report for the school district analysis (README.md)
  
# Summary:

  ## Thomas High School Scores
   -  Math and reading scores for ninth graders at Thomas High School were updated with 'NaN'

  ## Thomas High School math scores:
  - Ninth grade math scores were replaced with NaN. 
  - Thomas High School 10th, 11th, and 12th grade math scores are as follows: 83.1, 83.5, and 83.5.

  ## Thomas High School reading scores:
  - Ninth grade math scores were replaced with NaN. 
  - Thomas High School 10th, 11th, and 12th grade reading scores are: 84.3, 83.6, and 83.8.

## Ways Thomas High School school rankings:
- Top 5 School Rankings were Afftected
    - Thomas High school dropped out of the top 5 high schools in the district
    - Wright High School moved into the top 5 high schools in the district
- Bottom 5 high schools were unaffected

## How removing student scores affected other reports:
- **Thomas High School had no data to report for 9th grade math and reading scores**

- **Scores by school spending chaged around the $601-650 range:**
     - Percentage passing math dropped from 73% to 67%
     - Percentage passing reading dropped from 84% to 77%
     - Overall passing percentage dropped from 63% to 56%
     
- **Scores by school size (medium-sized schools, 1000-2000)**
     - Percentage passing math dropped from 94% to 85%
     - Percentage passing reading dropped from 97% to 91%
     - Overall passing percentage dropped from 91% to 85%
     
- **Scores by schools type:**
     - Percentage passing math dropped from 94% to 90%
     - Percentage passing reading dropped from 97% to 93%
     - Overall passing percentage dropped from 90% to 87%

