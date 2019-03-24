For this CodeCademy project, I use SciPy to analyze data and perform statistical tests for a fictional app called FetchMaker. The goal of FetchMaker is to pair dogs availavle for adoption with perspective owners. 

In order to find the best fit for a perspective owner, I explored information such as weight, age, tail length, color, and whether or not the dog is a rescue (which was stored as a boolean value). 

The dog breeds availavle are whippet, terrier, shihtzu, pitbull, rottweiler, poodle, chihuahua, and greyhound. 

I used an ANOVA function to compare weights between the whippets, terriers and pitbulls. I then used a Tukey's Range Test to find which pair hard the significant difference. <br>

<img width="465" alt="Screen Shot 2019-03-24 at 9 17 19 PM" src="https://user-images.githubusercontent.com/46868984/54885628-8d997100-4e7e-11e9-88ae-3315eb56d0e5.png">


I also created a Chi Square contingency table and performed a Chi Square test to compare colors between whippets and shihtzus. Because the pvalue of the test was less than .05, I was able to determine that there is a signifiant difference between pooble and shihtzu colors. 

<img width="718" alt="Screen Shot 2019-03-24 at 9 16 38 PM" src="https://user-images.githubusercontent.com/46868984/54885629-a1dd6e00-4e7e-11e9-9339-7d38b98cbb5d.png">

