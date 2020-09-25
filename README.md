# Analyze the Effect of Class Type on First Grade Math Scores Using Two-way ANOVA

## Abstract

This study is based on the Project Student-Teacher Achievement Ratio (STAR) public access data set, assessing the effect of class size on the performance of teachers. The full data set contains 11,601 observations on 379 variables. The Project STAR data set contains data on test scores, treatment groups, and student and teacher characteristics over the four years of the experiment, from the academic year 1985–1986 to the academic year 1988–1989. All students were randomly assigned to one of three class types, including small class, regular class, and regular-with-aide class, and all teachers and students were also randomly assigned to the classes. The questions we were interested in are:

* Whether there is an association between class types and teachers’ teaching quality
* Whether we could make causal inference between class types and teachers’ teaching quality

To study these problems, we first defined a measure of teachers' teaching quality. The measure we chose is the median math scores of all students taught by each teacher. Then, we analyzed the data by using two-way ANOVA. After the model assumptions justified, Tukey’s test was applied and it showed that the differences between small class and regular class, small class and regular with aid calss were significant; but the difference between and regular calss and regular with aid calss was not significant. By further applying potential outcomes framewrok and Fish's Exact P-value to do causal inference, we draw the conclusion that class size does have an effect on first-grade teachers’ teaching quality. 

## The files are used for:
<table>
<tr><td width="400px">File Name</td><td width="400px">Description</td></tr>
<tr><td width="400px">Analyze the Effect of Class Type on First Grade Math Scores Using Two-way ANOVA.pdf</td><td width="400px">Main file with plots and conclusions</td></tr>
<tr><td width="400px">STAR_Students.sav</td><td width="400px">Dataset</td></tr>
<tr><td width="400px">R Code.Rmd</td><td width="400px">Related code</td></tr>
<tr><td width="400px">t_statistics.txt</td><td width="400px">The file for simulated values</td></tr>
<tr><td width="400px">ppt.pptx</td><td width="400px">PPT used for presentation</td></tr>
</table>
