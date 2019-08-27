---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 3 V2               <br/>
**Topic**:  Statistics <br/>
**Amount of time**: 60 minutes  <br/>
**Author**: Alison Peebles Madigan and Laura Colon Melendez

Ported from the ds-lesson-starters repository [here](https://github.com/learn-co-curriculum/ds-lessons-starter/tree/master/hypothesis_testing) and [here](). 


***

#### Lesson Summary:

A discussion of concepts related to hypothesis testing is motivated by a word problem where students perform two-tailed and one-tailed one-sample z-tests. In this discussion, students apply the different steps necessary to perform a hypothesis test (setting the null and alternative hypothesis, determining the critical value of the relevant test statistic, performing the actual test, and deciding whether to reject of fail to reject the null hypothesis). Concepts related to hypothesis tests, such as the null hypothesis, alternative hypothesis, significance threshold ($\alpha$), and p-values are discussed. Then, the distinction between z-tests and t-tests is discussed. Students then work through z-test and t-test examples, stating hypothesis, computing test statistics, comparing against critical test statistics, and making decisions to reject or not reject the null hypothesis.


#### Topic:

Statistics

#### Learn.co material:

[Introduction](https://github.com/learn-co-curriculum/dsc-hypothesis-testing-intro)

[Introduction to Experimental Design](https://github.com/learn-co-curriculum/dsc-experimental-design)

[P-values and the Null Hypothesis](https://github.com/learn-co-curriculum/dsc-p-values-and-null-hypothesis)

[Conducting T-Tests](https://github.com/learn-co-curriculum/dsc-t-tests)

[One Sample T-Test - Lab](https://github.com/learn-co-curriculum/dsc-one-sample-t-tests-lab)

[Two Sample T-Test - Lab](https://github.com/learn-co-curriculum/dsc-two-sample-t-tests-lab)

[Section Recap](https://github.com/learn-co-curriculum/dsc-hypothesis-testing-section-recap)


#### Prerequisite knowledge/ Prework:

Normal distribution

Standard normal distribution

Student's t-distribution

Central Limit Theorem


#### Learning goals for this lesson:

* Students can define the null and alternative hypothesis. 
* Students understand the difference between one-tailed and two-tailed tests.  
* Students can define the significance threshold $\alpha$ and its relation to p-value. 
* Students differentiate when to use z-tests vs. t-tests.
* Students perform z-tests and t-tests using python libraries. 

Relevant learning goals from Airtable: 

* 


#### Misconceptions / Notes

A common misconception is that you can accept the alternative hypothesis. 

> This is not true. 

> We either _reject_ or _fail to reject_ the null hypothesis at a given significance level $\alpha$. 


#### Materials
- Ipython notebook

#### Vocab / Concepts 

* Hypothesis testing
* Null hypothesis
* Alternative hypothesis
* p-values 
* One-sample z-test
* One- and two-sample t-tests

#### Lesson Outline:

* Hypothesis testing (20 minutes)
    * Jumpstart the discussion with an example: give students a word problem for a two-sided one-sample z-test. 
        * Ask students to write the null and alternative hypothesis. 
        * Discuss the importance of the significance threshold $\alpha$: business applications.
        * What if we were performing a one-sided test? What would change? 
    * As the students work thru the problem, reinforce the "recipe" for performing hypothesis tests.
    * This is a long example: it is meant to highlight how you can reach different decisions dependening on what you're testing (one-tailed vs two-tailed test) and the significance level used. 
    
* When do we use z-tests and when do we use t-tests? (5 minutes)
    * z-test: large enough sample size, known population variance
    * t-test: small sample sizes, unknown population variance

* Examples: One-sample z-tests, one-sample and two-sample t-tests (20 minutes)

* Summary (5 minutes)

Wiggle room: 5 minutes
