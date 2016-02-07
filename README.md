# essentials-gradebook
Grade calculator integrating different sources.

## Grade Calculator

Goal: Calculates the final grade given the weight of each hwk, midterm, final exam and lab report. The freshmen physics courses at Hunter College of The City University of New York are split into Lecture and Labs. Lecture accounts for 85% of the final grade and labs for 15%. The labs and lecture are taught by different instructors. Combine the data by id number to calculate the final grade.

### The lab data
* The last two columns represent quiz 1 and quiz 2. Each quiz is graded on the scale of 0-20. Each quiz is worth 10% of the lab grade.
* Columns 1-12 are grades from lab reports. They are graded in the scale of 0-100. The lowest two should be dropped when calculating the final lab grade, take the best 10 out of 12. The lab reports are worth 80% of the lab grade. The students must have minimum of 10 labs to recieve a passing grade.

### The Lecture data
There are two midterms and a final:
* The lowest midterm is worth 20% and the highest 35%.
* The final exam is worth 45%.
