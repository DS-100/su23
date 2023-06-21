---
layout: page
title: Home / Schedule
nav_order: 1
description: A week-to-week description of the content covered in the course.
course:
  edstem: https://edstem.org/us/courses/33744/
  faq: https://ds100.org/sp23faq
currWeekNumber: 1
---

# Data 100: Principles and Techniques of Data Science

{: .mb-2 }
UC Berkeley, Summer 2023
{: .mb-0 .fs-6 .text-grey-dk-000 }


[Ed](https://edstem.org/us/courses/40266){:target="_blank" .btn .btn-ed .mr-1 }
[Datahub](http://data100.datahub.berkeley.edu/){:target="_blank" .btn .btn-datahub .mr-1 }
[Gradescope](https://www.gradescope.com/courses/546710){:target="_blank" .btn .btn-gradescope .mr-1 }
[Extenuating Circumstances](https://forms.gle/GRREdhkik6bKm9bJA){:target="_blank .btn .btn-blue .mr-1}

<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

{: .highlight }
> Students who enrolled in the class after 6/20: email [data100.instructors@berkeley.edu](mailto:data100.instructors@berkeley.edu) so we can onboard you to the class.
>
> Frequently Asked Questions: Before posting on the [class Ed](https://edstem.org/us/courses/40266), please read the [class FAQ page](https://ds100.org/su23faq/).
>
> The [Syllabus](syllabus) contains a detailed explanation of how each course component will work this Summer, please take time to take a look.


<a name="schedule"></a>
## Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}

