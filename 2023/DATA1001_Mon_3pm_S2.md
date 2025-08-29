---
layout: default
title: DATA1001 Mon 3pm S2
parent: 2023
nav_order: 3
---

# DATA1001 Monday 3pm Semester 2

{: .note }
> **Substitue**
>
> Hi! My name is Tom and I'm filling in for your regular tutor for the first two weeks of term. This page here  will not be updated past week two.

{: .warning }
> **Assessment Dates**
>
> Rough assessment dates have been provided below. These have been added purely to help you have an idea about what is coming up. These assessment dates should not be taken as fact. It is on the onus of students to check Canvas, EdStem and the Unit of Study outline.

{: .note }
> **Extra Help/Staff Contact**
>
> Any extra help about course material should be asked on EdStem.

### Important Links

- [Canvas](https://canvas.sydney.edu.au/courses/51659)

- [Unit of Study Outline](https://www.sydney.edu.au/units/DATA1001/2023-S2C-ND-CC)

### Calendar

Week | Slides | Class Notes | Misc. | Further Learning | Assessments
:---|:---|:---|:---|:---|:---
Week 1<br>(Jul 31) | [Introduction](https://drive.google.com/file/d/1FiTEjBrwTm69vT5pnR4txzlInn_IOTba/view?usp=drive_link)<br>[Lab 1](https://drive.google.com/file/d/1CwGJdeN8QC82dt4ZDJO-mEkZikKDJ5_y/view?usp=sharing) | [Lab_1.Rmd](https://drive.google.com/file/d/15rcF6Geg6-mm9QsmEIV-FoOz43-QlP-T/view?usp=drive_link)<br>[Lab_1.html](https://drive.google.com/file/d/1ceFrxg8mKd_iJ9-96dx3bb-Pt1sfZ3vx/view?usp=drive_link) | [Software Installation Guide](https://canvas.sydney.edu.au/courses/51659/pages/how-to-install-r-slash-rstudio?module_item_id=1955526)<br>We won't have much time in this lab to debug R installation issues. Please pop in to the [drop in sessions](https://canvas.sydney.edu.au/courses/51659/pages/drop-ins-+-ed) if you need help!| [Britannica Simpson's Paradox article](https://www.britannica.com/topic/Simpsons-paradox)<br>[R Markdown Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) | Evaluate quiz 1 (Aug 6)
Week 2<br>(Aug 7) | [Lab 2](https://drive.google.com/file/d/1W-y2EZ6Erzya8TWmWuCSm8IjqsLFhIJ4/view?usp=sharing) | [Lab_2.Rmd]([https://drive.google.com/file/d/1kXST7IZ1YlMeb4aboqD1b_wO1uUm_w_Z/view?usp=drive_link](https://drive.google.com/file/d/1kXST7IZ1YlMeb4aboqD1b_wO1uUm_w_Z/view?usp=drive_link))<br>[Lab_2.html](https://drive.google.com/file/d/134unqr4YHABNKNkJBm0cTc7K7CWfwVMB/view?usp=drive_link)| See the "Lab_2" html or Rmd files to the left for examples of customising histograms. | [ggplot2 Cheat Sheet](https://www.maths.usyd.edu.au/u/UG/SM/STAT3022/r/current/Misc/data-visualization-2.1.pdf)<br>[Article on how to pick the right chart type](https://eazybi.com/blog/data-visualization-and-chart-types#pie-charts-and-donut-charts)| Evaluate quiz 2 (Aug 13)
Week 3<br>(Aug 14) | [Lab 3](https://drive.google.com/file/d/1P10U2mL6tLVUYMBxEPXJN0hLW9ePJqJ7/view?usp=drive_link) | [Lab_3.Rmd](https://drive.google.com/file/d/1WYnSfhn3BBoS3x-SGc-c21ySdRC519EG/view?usp=drive_link)<br>[Lab_3.html](https://drive.google.com/file/d/19tElrbU5thXIi7htY-C1BAOdSvy24EdE/view?usp=drive_link) | Please see the "Week 3: Notes/Clarifications" section below for claricfication on quartiles in R! | -- | Evaluate quiz 3 (Aug 20)
Week 4<br>(Aug 21) | [Lab 4](https://drive.google.com/file/d/1vw3Huuqca-zI51Cm-KsD6qniL0Xn8wHG/view?usp=drive_link) | [Lab_4.Rmd](https://drive.google.com/file/d/1Ai-q6ZiehC4HmeKVcKqVInb_bEf4wzAD/view?usp=drive_link)<br>[Lab_4.html](https://drive.google.com/file/d/1Z9tvOd6bXBKuqZVLDraEoNO2p29I0c_3/view?usp=drive_link) | -- | -- | Project 1 Individual and Group Parts Due (Aug 25)<br>Evaluate quiz 4 (Aug 27)
Week 5<br>(Aug 28) | -- | -- | Regular tutor back to campus. | -- | --

----

### **Week 3: Notes/Clarifications**

<br>

In the tutorial, there was a question where we were provided the following list of data: ```x <- c(1,2,3,4,5,6,7,8,9,10)```. When we ran ```summary(x)``` on the data, we were given that the first quartile has the value 3.25, and that the third quartile has the value 7.75. This would seem to go against the convention taught in NSW highschools, where typically we would have that the first quartile has the value 3, and the third quartile has the value 8. Shoutout to the group who noticed the inconsistency here! So what's going on?

Firstly, a note has been added to the bottom of the "3.3 Challenge" Canvas page.

But, to explain it here, there are different ways of calculating quantiles. In fact, if you run `?quantile`, you'll see nine different ways of calculating them. In practice though, we just use ggplot to create our boxplots, so we'll stick with the output that ggplot uses.

If you're interested in further reading, check out the following links:

- https://bookdown.org/dli/rguide/descriptive-statistics-for-a-vector.html#describing-distribution

- https://stackoverflow.com/questions/40634693/lower-and-upper-quartiles-in-boxplot-in-r/40639848#40639848

- https://stackoverflow.com/questions/70637398/calculating-the-five-number-summary-in-r-results-in-incorrect-values
