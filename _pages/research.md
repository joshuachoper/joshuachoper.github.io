---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## The Opportunity Structure for Career Mobility and Inequality

My dissertation investigates how the structure of jobs in local labor markets shapes inequality in workers' career paths. I examine how occupational polarization and occupational segregation by race and gender have occurred unevenly across the US, reshaping local structures of economic opportunity and amplifying inequalities in attainment and mobility. I demonstrate that polarization is associated with higher earnings inequality at the beginning of workers’ careers and a stronger persistence in earnings inequality as workers age. This effect is particularly strong in more recent cohorts where earnings grow rapidly for high-earners in highly polarized local labor markets. Advantages from polarization disproportionately accrue to workers in managerial and professional occupations. While polarization amplifies racial and gender inequalities, its effect varies between regions depending on levels of racial and gender segregation between occupations, higlighting how the effects of economic restructuring on racial and gender inequalities depend on occupational closure.

### Working papers
* [Local Labor Market Polarization and Inequality in Career Earnings Mobility](http://joshuachoper.github.io/files/localabmkt_pol.pdf)

## Causes and Consequences of Work Schedule Instability

My other research focuses on the organizational dynamics of work schedule inequality among low-wage service sector workers. I use survey data and vignette experiments from the Shift Project to examine how female managers contribute to work scheduling inequalities for their employees who are mothers through the lens of social identity theory. I find that motherhood advantages in work scheduling present under male managers shrink considerably under female managers. Moreover, I find that queen bee behavior is limited to female managers without children, and it is only observed when female employees make scheduling requests specifically related to childcare. In co-authored work with Daniel Schneider and Kristen Harknett [published in the *ILR Review*](https://journals.sagepub.com/doi/abs/10.1177/00197939211048484), we find that schedule instability substantially increases turnover, largely through its negative effects on job satisfaction and work-family conflict. We show that this turnover results in earnings losses due to relatively long bouts of unemployment and only produces earnings gains upon reemployment for some workers.

### Working papers
* [Managing Motherhood: How "Queen Bee" Managers in the US Service Sector Reduce Motherhood Advantages in Work Scheduling](http://joshuachoper.github.io/files/queenbees.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
