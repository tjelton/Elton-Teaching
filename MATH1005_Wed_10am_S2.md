---
layout: default
title: MATH1005 Wed 10am S2
parent: 2023
nav_order: 4
---

# MATH1005 Wednesady 10am Semester 2

{: .warning }
> **Assessment Dates**
>
> Rough assessment dates have been provided below. These have been added purely to help you have an idea about what is coming up. These assessment dates should not be taken as fact. It is on the onus of students to check Canvas, EdStem and the Unit of Study outline.

{: .note }
> **Extra Help/Staff Contact**
>
> Any extra help about course material should be asked on EdStem. Students are free to email with personal issues, but questions about content will be redirected to EdStem.

### Important Links

- [Canvas](https://canvas.sydney.edu.au/courses/53110)

- [Lecture Resources](https://canvas.sydney.edu.au/courses/53110/pages/class-resources?module_item_id=2017075)

- [Unit of Study Outline](https://www.sydney.edu.au/units/MATH1005/2023-S2C-ND-CC)

### Calendar

Week | Slides | Class Notes | Misc. | Further Learning | Assessments
:---|:---|:---|:---|:---|:---
Week 1<br>(Aug 2) | [Introduction](https://drive.google.com/file/d/1FiTEjBrwTm69vT5pnR4txzlInn_IOTba/view?usp=drive_link) | [Lab sheet from class](https://drive.google.com/file/d/10FNQzetqZ41YeAWGqgHmh4TdUtI3l83K/view?usp=drive_link)| -- | [Britannica Simpson’s Paradox Article](https://www.britannica.com/topic/Simpsons-paradox)<br>[R Markdown Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) | RQuiz1: Design of Experiments (Aug 6)
Week 2<br>(Aug 9) | [Lab 2](https://drive.google.com/file/d/1EELFKarXcH3uB4qTQOFAmwfo8HI6HeNt/view?usp=drive_link) | [Lab sheet from class](https://drive.google.com/file/d/13pcK1_995ZZ5er2ZqjnFqLklc4dBfsBJ/view?usp=drive_link)<br>*Please read clarification 3* | Please see below for notes and clarifications from todays lab. | [Article on how to pick the right chart type](https://eazybi.com/blog/data-visualization-and-chart-types#pie-charts-and-donut-charts)<br>[Interpreting skewness from a boxplot](https://www.simplypsychology.org/boxplots.html#:~:text=Box%20plots%20are%20useful%20as%20they%20show%20the%20skewness%20of%20a%20data%20set&text=When%20the%20median%20is%20closer%20to%20the%20top%20of%20the,negatively%20skewed%20(skewed%20left).) |  RQuiz2: Data & Graphical Summaries (Aug 13)
Week 3<br>(Aug 16) | [Lab 3](https://drive.google.com/file/d/1p7msz1h_ivdITuEzkziYz5Q_k_BpNFLF/view?usp=drive_link)<br>[Code for graph in slides](https://drive.google.com/file/d/1xcdztlvmGNffHNLlC84HIiLrBShiMlDb/view?usp=drive_link) | [Lab sheet from class](https://drive.google.com/file/d/1n1RcqSitjZrtH8J0dVGs87WIQKRG7n_D/view?usp=drive_link) | -- | -- | RQuiz3: Numerical Summaries (Aug 20)
Week 4<br>(Aug 23) | [Lab 4](https://drive.google.com/file/d/1-TRha3Uk7VE39V_o9poHuSjzF9NDn-73/view?usp=drive_link) | [Lab sheet from class](https://drive.google.com/file/d/1hN6wWmJ7EOKInem77VrsxgvUILGX7f7U/view?usp=drive_link) | Download the lab sheet for some tips on how to approach manual calculations for the normal distribution. | -- | RQuiz4: Normal Model (Aug 27)
Week 5<br>(Aug 30) | No slides this week. Please scroll below for week 5 notes. | [Lab 5](https://drive.google.com/file/d/1EvlQYp9FHhr3ghBsKalnLirxutIhMOo7/view?usp=drive_link)  | -- | -- | RQuiz5: Linear Model (Sep 3)
Census Date<br>(Aug 31) | -- | -- | Last day to drop a unit without incurring financial or academic penalty. | -- | --
Week 6<br>(Sep 6) | -- | -- | -- | [Can computer's generate random numbers?](https://engineering.mit.edu/engage/ask-an-engineer/can-a-computer-generate-a-truly-random-number/) | RQuiz6: Understanding Chance (Sep 10)
Week 7<br>(Sep 13) | -- | -- | -- | -- | --
Week 8<br>(Sep 20) | -- | -- | -- | -- | --
Assessment<br>(Sep 22) | -- | -- | -- | -- | Assignment 1
Mid Semester Break<br>(Sep 25-29) | -- | -- | No class. | -- | --
Week 9<br>(Oct 4) | -- | -- | -- | -- | --
Week 10<br>(Oct 11) | -- | -- | -- | -- | --
Week 11<br>(Oct 18) | -- | -- | -- | -- | --
Assessment<br>(Oct 20) | -- | -- | -- | -- | Assignment 2
Week 12<br>(Oct 25) | -- | -- | -- | -- | --
Week 13<br>(Nov 1) | -- | -- | Last week of classes. | -- | --
STUVAC<br>(Nov 6-10) | -- | -- | Study vacation. | -- | --
Exam Period<br>(Nov 13-25) | -- | -- | Exam data to be released by the University. | -- | --

----

### **Week 2: Notes/Clarifications**

<br>

**<u>Clarification 1</u>**

In the week 2 slides, on slide 10, the "qualitative" and "quantitative" labels in the flow chart were in the wrong location. The slides have been re-uploaded with the "qualtiative" and "quantitative" labels in the correct position.

**<u>Clarification 2</u>**

In the tutorial, I mentioned that we would soon be learning how to use ggplot to create our plots. This is actually **not** the case with MATH1005. If you are enjoying R and think that data science is something you would like to pursue, I would definetly recommend checking out ggplot!

**<u>Clarification 3</u>**

I was asked in class what ```las=2``` inside the barplot code does. This changes the x-axis category names to be vertical.

I incorrectly said in class that this removes the column without a category name. This is incorrect! The reason why there apeared to be a missing title was that the string "Wednesday" was too long to be shown horizontally.

**<u>Notes - Complex Boxplot</u>**

In class, we didn't quite get enough time to finish some of the harder plotting questions. One such question was regarding investigating the pattern between "age" and "crash type". Here we are considering one quantiative variable (age), and one qualitative variable (crash type). This means that boxplots would be a good choice.

The first thing we do is select the "age" data: ```age = road$Age```

Now, if we were to run ```class(age)```, we would see that the age list is of type character (which implies it is currently a qualitative variable). We actually want to change it to a numeric variable, and we can do that by running, ```ageN = as.numeric(age)```. We now have a variable called ```ageN``` which stores the ages as a numeric type.

We also need to extract the crash type, which we can do by: ```crash_type = road$Crash_Type```

Now we can create the boxplot using the following code: ```boxplot(ageN ~ crash_type, horizontal=T, col=c("light blue", "light green", "light pink"), main = "Age distribution by crash type")```

How does this work? Well, the main thing is that we need to tell R how we want the boxplots to be formed. ```ageN ~ crash_type``` informs R that we want "ageN" to be the value that we are finding the distribution of, and we want to seperate the ages by ```crash_type```. The other parameters should be fairly straight forward to understand - if they're not, change them and see what happens!

To visualise what this plot looks like you can check out 2.0.2 of the "Lab Sheet From Class" in the "Class Notes" section of week 2.

There is one more boxplot in the explore section, but try this out youself! We'll go through it next tutorial.

----

### **Week 5: Notes**

For the first part of the tutorial, we went through the group project. Here, I wanted to provide some broad thoughts about how to go about sourcing addition research in scientific reports.

Whenever we write something in a scientific report that did not come from us, it's important that we also include a source to add some weight behind what we have just claimed. Citing is really important, because it shows that we didn't simply make up what we claimed.

Here is a short excerpt (that has been slightly modified) from a report I wrote for one of my university classes:

> Despite concerns that in industry, women only account for 25% of computer-science related jobs (Daley, 2021), this does not hold among the people which responded to the DATA2x02 survey according to the Chi-squared goodness of fit test. In fact, 36% of DATA2x02 students identify as female, which is much larger than 25%.

Now, I'm not claiming that my above excerpt is a masterpiece, but I do think it does a good job of showing how we can intertwine additional research into our reports. In the above excerpt, I am making a claim that in "industry, womeon only account for 25% of computer-science related jobs." But I am no expert in this field, and so I have to share where I got this "25%" value from.

I do this by including what is called an in-text citation, evident where in brackets I write "Daley, 2021". This comes straight after I mention this "25%" number which I gathered from a source online. I include the citation to indicate that this figure is not my own observation, but from somone else (who would know much more about this than me).

In the reference list later in my report, I would have a full citation for Daley, written as:

> Daley, S. (2021) Women in Tech Statistics Show the Industry Has a Long Way to Go. https://builtin.com/women-tech/women-in-tech-workplace-statistics

In a nut shell, whenever we are making a claim that does not come from our own research, we have to include a reference to where we found that claim.

There are many different referencing styles that you can use, but in this course we require APA citations. You can find more information about how to write APA citations and in-text citations here:

- [Official USyd guide](https://libguides.library.usyd.edu.au/citation/apa7)

- [Many exmaples here from Griffith University](https://www.griffith.edu.au/library/study/referencing/apa-7)

----
