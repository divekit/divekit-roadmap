---
type: stakeholder
acronym: fabianKrampe
name: Fabian Krampe
role: wmaProg
relationship_to_project: >
    Anwender des Systems in mehreren Lehrveranstaltungen. Interessiert an sinnvoller Weiterentwicklung, 
    möchte eigene Ideen einbringen. 
history:
    v1:
        date: 2021-01-22
        comment: created initially
---

## Tätigkeitsgebiete 

(mehr Informationen über Fabians Schwerpunkte in der Lehre)


Bitte in das HTML-File kopieren (Detail View von Stakeholder)
{% assign stakeholderRole = site.stakeholderRoles | where: "acronym", page.role | first %}
{% assign urlString = "stakeholderRoles/" | append: stakeholderRole.acronym %}
<li ><a href="{{ site.url }}{{ urlString | relative_url }}">{{ stakeholderRole.description }}</a></li>