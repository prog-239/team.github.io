### Преподаватели

{% for tutor in site.tutors %}
{% assign ghlink = "https://github.com/" | append tutor.github %}
- {{ tutor.lastname }} {{ tutor.firstname }} {{ "\[" append tutor.github append "\]\(" | append ghlink | append "\)" }}
{% endfor %}


### Студенты

{% for student in site.students %}
- {{ student.lastname }} {{ student.firstname }} {{ "https://github.com/" | append student.github }}
{% endfor %}
