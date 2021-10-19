# School_District_Analysis

## Overview of the school district analysis:
  In this analysis, the math scores and reading scores for Thomas High School 9th grders had to be dropped because of some evidenc showing academic dishonesty. Therefore, the school_distric data was re-analyzed to see whether eliminating the reading and math score for Thoma High School 9th grader have influences on the overal analyis. We compared how school sistrict summary data is affected, and the changes of scores by school spending/scores by school size/scores by school type.  

## Results
  - How is the district summary affected? 
    By comparing the data summary of the original analysis and the data taking away Thomas High School 9th grader scores, there is no change. 
    
    Figure 1: district_summary_original data
    
    ![distric_summary_original](https://user-images.githubusercontent.com/90361056/137825734-0c48417b-01a5-4a78-b845-047dde3796fd.PNG)

    Figure 2: district_aummary_Thomas High School 9th grader scores removed
    
    ![distric_summary_challenge](https://user-images.githubusercontent.com/90361056/137825764-848606fa-bf7b-4706-b6e8-9151d4f646d3.PNG)


- How is the school summary affected?
    Removing homas High School 9th grader scores has very little influence on the average scores and score passing percentage, the difference is < 0.5%
    
    Figure 3: school_summary_original data
    
    ![school_summary_original](https://user-images.githubusercontent.com/90361056/137825569-1d001468-bbb9-41f6-b149-f46eb58e18af.PNG)

    Figure 4: school_summary_Thomas High School 9th grader scores removed
    
    ![school_summary_challenge](https://user-images.githubusercontent.com/90361056/137826457-cd028820-be3d-40e5-a381-5e8e2ca7e3d8.PNG)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    From the results above, we can see replacing 9th graders' math and reading scores doesn't significant affect Thomas High School’s performance relative to the other schools.
    
- How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
    Replacing homas High School 9th grader scores with NaN doesn't affect other grade's performance on math and reading scores
  
  * Scores by school spending
  
    Figure 5: school_spending_original data
    
    ![school_spending_original](https://user-images.githubusercontent.com/90361056/137828335-8ca0c4c7-efc9-4e04-b75a-f940df408a57.PNG)

    Figure 6: school_spending_Thomas High School 9th grader scores removed

    ![school_spending_challenge](https://user-images.githubusercontent.com/90361056/137828472-1430b8c9-14ba-4e70-8179-c072479fc9cd.PNG)

  * Scores by school size
  * Scores by school type
