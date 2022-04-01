# School District Analysis

## Project Overview:
The goal of this project is to provide an analysis for the school district that covers a snapshot of the district’s key metrics. These metrics include top 5 and bottom 5 performing schools, average math and reading score, and school performance.  Unfortunately, there was evidence to show academic dishonesty. After the analysis was completed, the information needed to be alerted, to remove Thomas High School’s ninth grade class. 
## Results: 

1. How is the district summary affected?
   1. After removing the 9th grade results from Thomas High School, the % of passing for math, reading and overall, all dropped slightly at the district summary level. The math went from 75% to 74.8%, the reading decreased from 85.8% to 85.7% and the overall passing % went from 65.2% to 64.9%.

### District Summary Original 
<img width="992" alt="District Summary Original" src="https://user-images.githubusercontent.com/99099706/161341224-f1a1dc93-6bc7-4c0a-8d81-580e039628a8.png">

### District Summary Revised
<img width="917" alt="District Summary Revised" src="https://user-images.githubusercontent.com/99099706/161341341-46a596ef-bf46-4a5f-ad05-159b5ed57905.png">

2. How is the school summary affected?
   2. Thomas High School was the only school affected. The original analysis showed Thomas High School with an overall 90.9% passing rate. When the math and reading scores were adjusted, Thomas High School overall passing percentage dropped down to a 90.6%. The original passing math score was 93.3% and when revised it became 93.2%. The original passing reading score was 97.3% and the revised score was 97.0%. 

### School Summary Original
<img width="991" alt="Summary Original" src="https://user-images.githubusercontent.com/99099706/161341446-00c25884-4f17-4260-ac49-aa8af72e294e.png">

### School Summary Revised
<img width="1000" alt="Summary Revised" src="https://user-images.githubusercontent.com/99099706/161341813-27f7bf97-5cee-4b9b-b071-7667a5cae0db.png">

3. How does replacing the ninth grader’s math and reading scores affect Thomas High School performance relative to the other schools?
   3. Relative to the other schools, taking out the ninth graders scores did not affect them from being the overall number two school across the district. 

4. How does replacing the ninth-grade scores affect the following:
   1. Math and reading scores by grade: Thomas High School’s ninth grade class was the only grade that was affected. Their new score became “nan”, while every other grade stayed the same. 
   2. Scores by school spending: The school spending per student was not affected, they stayed within the range of $631-645. 
   3. Scores by school size: Removing the ninth grade’s math and reading score did not affect the school size. They were able to stay within a medium school size. 
   4. Scores by school type: Charter school had a higher overall passing score compared to district schools. Thomas High School was not affected. 

### Size Summary 
<img width="796" alt="Size Summary" src="https://user-images.githubusercontent.com/99099706/161341919-4314b5cd-d874-4f5b-aeda-f774814af85c.png">

### Type Summary 
<img width="746" alt="Type Summary" src="https://user-images.githubusercontent.com/99099706/161342222-7d655f0d-42c9-4931-8c0e-0d1d704d0b7a.png">

## Summary: 
There were a few things that were changed when we updated the 9th grade reading and math scores to “nan” at Thomas High School. One thing was that the math and reading scores by grade summary now showed “nan” for the 9th grade at Thomas High School instead of their previous scores. Another thing that changed was Thomas High School’s overall passing % dropped by 0.3%. An additional change was that their math score dropped by 0.1% and their reading score dropped by 0.3% in the school summary. Finally, the updated scores changed the overall district summary as well, with math dropping by 0.2%, reading dropping by 0.1% and the overall district passing score dropping by 0.3%. Overall, updating the 9th grade scores of Thomas High School slightly decreased percentages both for their school and for the district summary in total. 
![image](https://user-images.githubusercontent.com/99099706/161342374-ff0196eb-db44-44c2-b6ee-83e185fbaf03.png)
