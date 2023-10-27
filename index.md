### Преподаватели

{% for tutor in site.tutors %}
- {{ tutor.lastname }} {{ tutor.firstname }} ({{ tutor.github }})
{% endfor %}


### Студенты

{% for student in site.students %}
- {{ student.lastname }} {{ student.firstname }} ({{ student.github }})
{% endfor %}
