---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## The Opportunity Structure for Career Mobility and Inequality

One strand of my research investigates how income and job mobility over the career contribute to economic inequality, with a particular focus on how the structure of jobs in local labor markets shapes inequality in workers' career paths. 

### Local Labor Market Polarization and Inequality in Career Earnings Mobility

In one working paper, I examine how occupational polarization has occurred unevenly across the US, reshaping local structures of economic opportunity and amplifying inequalities in attainment and mobility. I demonstrate that polarization is associated with higher earnings inequality at the beginning of workers’ careers and a stronger persistence in earnings inequality as workers age. This effect is particularly strong in more recent cohorts where earnings grow rapidly for high-earners in highly polarized local labor markets. Advantages from polarization disproportionately accrue to college-educated workers.

* [Working Paper](http://joshuachoper.github.io/files/localabmkt_pol.pdf)

### Stratification and Inequality After Job Displacement 

A second set of working papers consider inequalities in the economic consequences of job displacement. In one paper, I examine how earnings losses after job displacement differ by race, gender, and educational attainment due to differences in how workers' job tasks change after displacement. I argue that non-White, female, and non-college-educated workers' lower rank in the labor queue leads to disadvantageous patterns of task sorting that result in large earnings losses. I demonstrate that these workers disadvantageously experience larger reductions in the abstract and cognitive task content of their work and greater increases in their job's manual task intensity, explaining about 20 to 30 percent of inequalities in earnings losses by race and education. Moreover, I show that these disadvantages are exacerbated by declining demand for labor in middle-paying routine jobs (e.g. manufacturing or clerical work). This work demonstrates that inequalities in how employers rank workers in labor queues and changes to the job structure combine to create significant disadvantages in labor market matching processes that shape between-group inequalities in workers' ability to recover from job displacement.

* [Working Paper](http://joshuachoper.github.io/files/intro2_displacementtasks.pdf)(Revise and resubmit, *Socio-Economic Review*)

In another working paper, I investigate Black-White inequalities in the economic consequences of job displacement. This chapter is the first systematic study of Black-White inequalities after job displacement since Fairlie and Kletzer (1996). I show that Black-White inequalities in lost earnings from job displacement continued to narrow from the 1990s through the mid-2000s before massively increasing after the Great Recession. I demonstrate that rising Black-White inequality in lost earnings is largely limited to men and can be explained by Black workers' disadvantage in labor market matching after job displacement. Further, I demonstrate that observed racial inequalities in the costs of job displacement severely underestimate true inequalties in the effect of displacement. Using Heckman-corrected models, I demonstrate that after accounting for racial differences in selection into reemployment, there are significant racial disparities among men in the effect of displacement on earnings during recessions in the early 1980s, early 1990s and the Great Recession.

* [Working Paper](http://joshuachoper.github.io/files/racejobdisplacement_October2024.pdf)(Revise and resubmit, *Social Forces*)

### Modeling Intragenerational Mobility

Another working paper develops a novel quantitative approach to model how individuals' point of labor market entry shapes the full distribution of earnings ranks that workers may attain later in their career using quantile regressions. I argue that studies of intragenerational mobility should look beyond average outcomes to investigate how individuals' origins shape the entire range of economic opportunity they face. I demonstrate the utility of this approach through an analysis of cohort trends in intragenerational mobility and show how the floors, ceilings, and average rank mobility outcomes have changed over time.

* [Working Paper](http://joshuachoper.github.io/files/rankrank_cohort_v4.pdf)

## Inequality in the Low-Wage Labor Market
A second strand of my research examines inequalities in the low-wage labor market. This work considers the individual, organizational, and structural forces driving both the evolution of employment relations in the low-wage labor market and economic inequalities among low-wage workers.

### Causes and Consequences of Work Schedule Instability
One strand of this work focuses on the organizational dynamics of work schedule inequality among low-wage service sector workers. I use survey data and vignette experiments from the Shift Project to examine how female managers contribute to work scheduling inequalities for their employees who are mothers through the lens of expectation states theory and queen bee theories of management. I find that motherhood advantages in work scheduling present under male managers shrink considerably under female managers. Moreover, I find that queen bee behavior is limited to female managers without children, and it is only observed when female employees make scheduling requests specifically related to childcare. In co-authored work with Daniel Schneider and Kristen Harknett [published in the *ILR Review*](https://journals.sagepub.com/doi/abs/10.1177/00197939211048484), we find that schedule instability substantially increases turnover, largely through its negative effects on job satisfaction and work-family conflict. We show that this turnover results in earnings losses due to relatively long bouts of unemployment and only produces earnings gains upon reemployment for some workers.

* [Working Paper](http://joshuachoper.github.io/files/managers_vignettes_sept2024.pdf)(Revise and resubmit, *Social Forces*)

### Structural Foundations of Inequality the Low-Wage Labor Market
Another strand of my research examines the macroeconomic and structural drivers of inequality in the low-wage labor market. In a working paper (revise and resubmit, *American Sociological Review*, available upon request) co-authored with Lukas Lehner and Zachary Parolin, we examine the collision of buyer power (monopsony power) with worker power (union power) in the low-wage labor market through an analysis of Walmart Supercenter openings across US counties. We find that Walmart Supercenters are less likely to open in counties with higher union density, suggesting that worker power prevents increases in buyer power. However, we also find that after Walmart enters a county, worker power diminishes - union membership declines and the union earnings premium decreases. This study advances the sociological understanding of power struggles in the labor market.

In another working paper (available upon request) co-authored with Zachary Parolin, we argue that while economic inequality is often studied as a product of changing employment relations, the reverse is also true: economic inequality is a driver of labor market transformations. We investigate how economic inequality provides the necessary structural preconditions for the emergence of the online platform economy through an analysis of Uber's expansion throughout the US. We demonstrate that Uber's entry into and growth within local labor markets is strongly predicted by local levels of economic inequality, and this relationship is largely explained by high levels of financially insecure workers willing to accept precarious, low-paying gig work, and by demand for flexible, on-demand services among affluent consumers.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
