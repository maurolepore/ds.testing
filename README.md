
<!-- README.md is generated from README.Rmd. Please edit that file -->

A series of meetups about testing.

## Syllabus

We’ll loosely follow published resources by Hadley Wickham (see
“Resources” below). Each item in this syllabus corresponds to a meetup
and a GitHub
[release](https://github.com/2DegreesInvesting/ds.testing/releases) that
preserves a snapshot of this repository exactly as it was shown during
thee meetup.

### Introduction

This meetup covers the introduction to
[Testing](https://mastering-shiny.org/scaling-testing.html#scaling-testing)
from the book [Mastering Shiny](https://mastering-shiny.org), and maybe
the subsection
[Philosophy](https://mastering-shiny.org/scaling-testing.html#philosophy).
The following meetups will cover the mechanical aspects of testing with
testthat.

Objectives:

-   Understand why testing is useful and what is it.

-   Introduce the basic anatomy of a testthat test.

-   Introduce four levels of testing and announce which one level this
    series focuses on.

-   Discuss when you should write tests.

-   Discuss what we want to take away from this series.

### Next: Mechanics

-   [Testing
    functions](https://mastering-shiny.org/scaling-testing.html#testing-functions).

-   [Workflow](https://mastering-shiny.org/scaling-testing.html#workflow-1).

### Resources

-   [Mastering Shiny:
    Testing](htps://mastering-shiny.org/scaling-testing.html). This book
    chapter is the most recent effort by Hadley Wickham to teach
    testing. Beyond some specific details about testing Shiny apps
    (which this series won’t cover) it explains testing in general. It
    includes features in the recent release of testthat e3.

-   [R packages: Testing](https://r-pkgs.org/tests.html). This book
    chapter is a common reference to teach testing in R. If you read the
    previous resource, these are the useful bit from this chapter:

    -   [What to test](https://r-pkgs.org/tests.html#what-to-test).
    -   [Skipping a
        test](https://r-pkgs.org/tests.html#skipping-a-test).

-   [testthat](https://testthat.r-lib.org/index.html). This is the most
    popular R package for testing R code. The most important functions
    to know about are `expect_equal()`, `expect_error()`, and
    `expect_snapshot()`. They all have a number of convenient variants,
    all listed in the
    [Reference](https://testthat.r-lib.org/reference/index.html) section
    of the website.
