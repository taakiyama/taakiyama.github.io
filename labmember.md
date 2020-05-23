We are looking for new PhD students, Postdocs, and Master students to join the team!

Staff
{% assign number_printed = 0 %} {% for member in site.data.team_members %}
Tasuku Akiuyama   
Associate Professor   
Neuroscience Program Faculty  
Human Genetics and Genomics Program Faculty   
Director of Animal Studies at the Miami Itch Center

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

{% endif %}

{{ member.name }}
{{ member.info }}
email: <{{ member.email }}>
{% if member.number_educ == 1 %}

{{ member.education1 }}
{% endif %}
{% if member.number_educ == 2 %}

{{ member.education1 }}
{{ member.education2 }}
{% endif %}
{% if member.number_educ == 3 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{% endif %}
{% if member.number_educ == 4 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{{ member.education4 }}
{% endif %}
{% if member.number_educ == 5 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{{ member.education4 }}
{{ member.education5 }}
{% endif %}
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %} {% if even_odd == 1 %}

{% endif %}
Master and Bachelor Students
{% assign number_printed = 0 %} {% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

{% endif %}
{{ member.name }}
{{ member.info }}
email: <{{ member.email }}>
{% if member.number_educ == 1 %}

{{ member.education1 }}
{% endif %}
{% if member.number_educ == 2 %}

{{ member.education1 }}
{{ member.education2 }}
{% endif %}
{% if member.number_educ == 3 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{% endif %}
{% if member.number_educ == 4 %}

{{ member.education1 }}
{{ member.education2 }}
{{ member.education3 }}
{{ member.education4 }}
{% endif %}
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %} {% if even_odd == 1 %}

{% endif %}
Alumni
{% assign number_printed = 0 %} {% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}

{% endif %}

{{ member.name }}
{{ member.duration }}
Role: {{ member.info }}
{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %} {% if even_odd == 1 %}

{% endif %}
Former visitors, BSc/ MSc students
Visitors
{% for member in site.data.alumni_visitors %} {{ member.name }} {% endfor %}
Master students
{% for member in site.data.alumni_msc %} {{ member.name }} {% endfor %}
Bachelor Students
{% for member in site.data.alumni_bsc %} {{ member.name }} {% endfor %}
Administrative Support
Ellie van Rijsewijk is helping us (and other groups) with administration.
