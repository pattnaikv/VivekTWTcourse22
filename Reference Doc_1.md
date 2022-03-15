# This topic has a reference from the previous topic as part of final assignment

## [Reference Doc No 2](Reference Doc_2.md)

## **The Age and Name from the Titanic CSV file is published below**


{% for item in site.data.titanicdatafile %}
{{item.Name}}, {{item.Age}}
{%endfor%}




