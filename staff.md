---
layout: page
title: Staff
nav_order: 7
description: A listing of all the course staff members.
---

# Staff

Jump to: [Instructors](#inst), [Teaching Assistants](#tas), [Readers](#readers).

**Note:** Consult the [calendar]({{ site.baseurl }}/calendar) for the most up-to-date office hours for each GSI. All GSI Office Hours will be held in Warren 101B.

## Course Staff Email
Contact course staff via [Ed](https://edstem.org/us/courses/40266) with any questions or concerns. For sensitive matters, the staff email address [data100.instructors@berkeley.edu](mailto:data100.instructors@berkeley.edu) is monitored by the instructors and a few lead TAs.

<a name = 'inst'></a>

## Instructors

<div class="role">
  {% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

<a name = 'tas'></a>

## Teaching Assistants

<div class="role">
  {% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
  {% for staffer in teaching_assistants %}
  {{ staffer }}
  {% endfor %}
</div>

<!---
<a name = 'tutors'></a>

## Tutors

<div class="role">
  {% assign readers = site.staffers | where: 'role', 'Tutor' %}
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div>

-->


<a name = 'readers'></a>

## Readers

<div class="role">
  {% assign readers = site.staffers | where: 'role', 'Reader' %}
  {% for staffer in readers %}
  {{ staffer }}
  {% endfor %}
</div>