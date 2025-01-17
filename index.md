---
layout: page
title: Home / Schedule
nav_order: 1
description: A week-to-week description of the content covered in the course.
course:
  edstem: https://edstem.org/us/courses/33744/
  faq: https://ds100.org/fa23faq
currWeekNumber: 8
---

# Data 100: Principles and Techniques of Data Science

{: .mb-2 }
UC Berkeley, Fall 2023
{: .mb-0 .fs-6 .text-grey-dk-000 }


[comment]: <> ([Ed](){:target="_blank" .btn .btn-ed .mr-1 })
[Datahub](http://data100.datahub.berkeley.edu/){:target="_blank" .btn .btn-datahub .mr-1 }
[Gradescope](https://www.gradescope.com/courses/564792){:target="_blank" .btn .btn-gradescope .mr-1 }
[Extenuating Circumstances](https://forms.gle/pm7VYsDeCpaBMc9r6){:target="_blank" .btn .btn-blue .mr-1 }

<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

{: .highlight }
> Welcome to Data 100!

[//]: <> > Welcome to [Week 1](#week-{{page.currWeekNumber}})!


<a name="schedule"></a>
## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}

