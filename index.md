### Преподаватели

{% for tutor in tutors %}
- {{ tutor.lastname }} {{ tutor.firstname }} ({{ tutor.github }})
{% endfor %}


### Студенты

{% for student in students %}
- {{ student.lastname }} {{ student.firstname }} ({{ student.github }})
{% endfor %}
