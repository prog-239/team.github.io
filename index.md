### Преподаватели

{% for tutor in site.tutors %}
{% assign ghlink = "https://github.com/" | append: tutor.github %}
- {{ tutor.lastname }} {{ tutor.firstname }} [@{{tutor.github}}]({{ ghlink }})
{% endfor %}

### Студенты

{% for student in site.students %}
{% assign ghlink = "https://github.com/" | append: student.github %}
- {{ student.lastname }} {{ student.firstname }} [@{{student.github}}]({{ ghlink }})
{% endfor %}
