# PyCitySchool-Analysis
Using Anaconda and Python to analyze scores from school tests

## Purpose
A school district wanted data on math and reading scores of the districts high schools and their students. After review from the board it had appeared that Thomas High School's 9th grade class was cheating. The school board then asked for that data to be removed and analzed again for comparison. 

## Results
### District Summary
To determine how taking out the 461 9th graders at Thomas High School would affect the score, I turned their schools data to null data. This then lead me to recalculate the percentages of passing math and reading scores, as well as overall passing. The reason why the total count of students didn't change was because the count was run of the students ids. After removing the Thomas High School 9th graders the impact of the data made almost no change. 
#### Original Analysis:
![Original Analysis](https://user-images.githubusercontent.com/95777297/151724248-caca8f08-2b45-4cca-adad-03091892136a.png)
#### Adjusted Analysis:
![Adjusted Analysis 1](https://user-images.githubusercontent.com/95777297/151724482-ffcbc7c3-b35f-4eba-8743-224e5c5f9d91.png)

### School Summary
Thomas High School had an overall passing percentage of 90.6% which caused the board to be concerned that the students were cheating. To see the difference I calcuated the percentages of 10th-12th graders to see how the 9th graders impacted the overall results. 
#### Original Analysis: 
![Original school analysis](https://user-images.githubusercontent.com/95777297/151725328-273b8782-733b-4055-a31c-7d074c6144fa.png)
#### Adjusted Analysis: 
![Adjusted school analysis](https://user-images.githubusercontent.com/95777297/151725380-b5654ac9-37ef-455e-b592-3f83dce70997.png)

### Replacement Analysis 
In the original analysis, Thomas High School was ranked 2nd behind Cabrera High School. This high rank caused the board to be concerned. After replacing the 9th grade data, Thomas High School dropped several spots and landed in the 7th spot of the 15 schools. 
#### Original Analysis: 
![Replacement analysis original](https://user-images.githubusercontent.com/95777297/151726562-b8a4669e-60c1-4718-b5f5-c89b7d8ec09a.png)
#### Adjusted Analysis
![Replacement adjustment analysis](https://user-images.githubusercontent.com/95777297/151726947-7199ea7e-af26-43c6-946c-107e032ff54c.png)

## Affects of Replacing 9th Grade scores
### Math and Reading Scores by grade
In the first unaltared analysis, Thomas High Schools 9th grade math average was an 83.6% while the reading average was 83.7% for 9th graders. Afterwards I adjusted the scores so that Thomas High School 9th graders showed NaN.
#### Adjusted average math scores
![Adjusted math](https://user-images.githubusercontent.com/95777297/151728587-89e5288e-ac77-4ca4-932d-690fa6abab93.png)
#### Adjusted average reading scores
![Adjusted reading](https://user-images.githubusercontent.com/95777297/151728584-870e5271-8647-450b-88cf-077dfc796938.png)

### Scores by school spending
The spending range of Thomas High School is between $630-$644 per student. Because the changes were so minimal a hundredths place was needed to see the change. 
#### Original Analysis
![Original spending](https://user-images.githubusercontent.com/95777297/151730257-97fe5b5f-d16a-42d6-93a0-83f2ad77ccdb.png)
#### Adjusted Analysis
![Adjusted school spending](https://user-images.githubusercontent.com/95777297/151730262-8fb24fec-1a33-49cf-8695-79bc2681ad55.png)

### Scores by school size
Thomas High School is considered a medium sized school. The changes were so small the hundredths place was added. 
#### Original Analysis
![school size original](https://user-images.githubusercontent.com/95777297/151731022-a93dfb6b-1a23-4a4c-ac0d-170e132af658.png)
#### Adjusted Analysis
![School size adjusted](https://user-images.githubusercontent.com/95777297/151731038-3a98e08b-9db8-4112-ac14-c0f358ec4992.png)

### Scores by school type
Thomas High School is a charter school, so to see changes a hundredths place was added. 
#### Original Analysis
![school type original](https://user-images.githubusercontent.com/95777297/151734409-3b8eb520-d5f1-472a-9b81-23014da5f430.png)
#### Adjusted Analysis
![school type adjusted](https://user-images.githubusercontent.com/95777297/151734399-b3de4682-5de1-40ee-a0ed-fae1d0819d7d.png)

## Summary
1. The overall passing rate changed from 91% to 65% at Thomas High School when the data was adjusted. 
2. The Ranking of Thomas High School dropped from 2nd to 8th in their district.
3. Grade level data will show "Nan" in reports for 9th graders at Thomas High School. 
4. The average passing percentages of Math and Reading shifted when the data was adjusted. 

The biggest changes were shown when looked at data applicable to the school. Although when zoomed out and analyzed all the districts the data will look like minor changes. 
