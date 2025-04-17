# Automated Visual Regression and Accessibility Testing Made Easy

## Abstract

We all know automated testing saves time and catches bugs before they go out to production. But sometimes it feels too complicated, time consuming, and inconsistent to set up. In this talk, we’ll explore how you can easily create a consistent suite of automated visual regression and accessibility tests, dynamically generated from your site, that run on any local or CICD environment using Playwright and Docker. By the end, you’ll be able to integrate these tools into your own work stream, saving your team dozens of hours per week just like it has for mine!

Level: Intermediate+

Length: 30 mins

## Description

### Objectives

- Provide an overview on the benefits of automated testing and the inherit inconsistencies of visual regression and accessibility tests
- Deep dive into setting up the automated tests to dynamically generate from your site, Dockerizing them for local and CICD use, and setting up your GitHub or ADO pipelines to run the tests and produce detailed reports.

This talk is primarily geared towards intermediate+ frontend or full stack engineers looking to level-up their automated testing game. We'll begin by talking about what Playwright is and how it fits into our suite of testing tools. Then we'll deep dive into the visual regression and accessibility testing options we have, including dynamically generating these tests based on our site's navigation structure.

We'll explore how and why this particular type of testing can be flakey, which will transition us into the second part of the talk - Dockerizing our test suites so they can be run in a consistent environment across the engineering team and CICD pipelines. Once that's complete, we'll walk through how to integrate everything we've built into your CICD pipeline in GitHub and view detailed test results on a per-pipeline run basis for debugging.

## Delivered at

- Internal team workshops
- [React Miami 2025](https://www.reactmiami.com/speakers/mclenachen)
  - Slides: https://github.com/isabelacmor/talks/blob/master/slides/ReactMiami2025-AutomatedTesting.pdf
  - Code: https://github.com/isabelacmor/playwright-docker
