<h1 style="font-weight:normal" align="center">
  &nbsp;# hyenaR course material&nbsp;
</h1>

<base target="_blank">

This repository contains course material for teaching an introduction to the hyenaR package created to work with data from the [Ngorongoro Hyena Project](https://hyena-project.com/). Links for all course slides are provided below. For teachers, original source material for generating slides (.qmd files) are available in the `/source` folder of the repository.

**NOTE:** This repository does not contain any of the hyena data needed to run the code.

<!--
WE COULD LINK TO hyenaR or hyena project website/twitter
<div align="center">

&nbsp;&nbsp;&nbsp;:link: [Website][Website]&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;:speech_balloon: [Twitter][Twitter]&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;:necktie: [LinkedIn][LinkedIn]

</div>

Quick Link

[Twitter]:https://twitter.com/ldbailey255/
[LinkedIn]:https://www.linkedin.com/in/liam-bailey-446823118/
[Website]:https://liamdbailey.com/
-->

***

### [Lesson 1:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_1.html)

An introduction to hyenaR. Learn about how the Hyena Project data workflow is structured and the grammar of hyenaR.

***

### [Lesson 2:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_2.html)

A practical example of hyenaR. Use hyenaR to extract reproductive success data for males.

***

### [Lesson 3:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_3.html)

Introduce new hyenaR functions: `create_id_starting.table()`, `fetch_id_rank()`, and `reshape_row_date.seq()`.

Homework: Find the oldest individual in each main clan on 2000-01-01

***

### [Lesson 4:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_4.html)

Solutions for homework from Lesson 3. Introduce the `{lubridate}` and `{tidyr}` packages.

Homework: Find the average lifespan of uncensored adults.

***

### [Lesson 5:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_5.html)

Solutions for homework from Lesson 4.

Homework: Count annual sightings of jackal species.

***

### [Lesson 6:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_6.html)

Solutions for homework from Lesson 5. Recap what we've done so far.

***

### [Lesson 7:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_7.html)

Discussing the 'overlap' argument in `hyneaR` in detail. How to deal with NAs in your data.

***

### [Lesson 8:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_8.html)

Introduce new hyenaR version v0.9.99994. Changes to relatedness functions, `create_id_starting.table()`, and adding functions for weather data.

***

### [Lesson 9:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_9.html)

Introduce new hyenaR version v0.9.99994. Changes to relatedness functions, `create_id_starting.table()`, and adding functions for weather data.

Homework: Identify the most productive year (most births) for each clan.

***

### [Lesson 10:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_10.html)

Introduce `create_sample_starting.table()`. Introduce the `{stringr}` package and how to work with text data.

***

### [Lesson 11:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_11.html)

More detail about `group_by()` and `summarise()` from the `{dplyr}` package. Consider different ways to count data. Recap how to deal with censored data.

***

### [Lesson 12:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_12.html)

A practical application of `hyenaR`: Generate a list of females and males of main clans with offspring that survived to adulthood (2y), in descending order, and with the information of whether the number of offspring is censored or not. Introduce the `{waldo}` package to compare objects in R.

***

### [Lesson 13:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_13.html)

Solution for homework from Lesson 10. Introduce `{skimr}` package to inspect data.

***

### [Lesson 14:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_14.html)

A practical application of `hyenaR`: List of all adults of main clans with their highest lifetime rank. Include some basic plotting with `{ggplot2}`.

***

### [Lesson 15:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_15.html)

A practical application of `hyenaR`: Extract monthly female reproduction and clan size for Airstrip. Build a model to study the relationship.

***

### [Lesson 16:](https://hyenaproject.github.io/hyenaR_course/hyenaR_teaching_16.html)

Running for loops in R. Introduce the `{purrr}` package that can be used for looping in the tidyverse.

***
<!-- 
#### Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)
<div style="width:300px; height:200px">
<img src=https://camo.githubusercontent.com/00f7814990f36f84c5ea74cba887385d8a2f36be/68747470733a2f2f646f63732e636c6f7564706f7373652e636f6d2f696d616765732f63632d62792d6e632d73612e706e67 alt="" height="42">
</div>
--!>