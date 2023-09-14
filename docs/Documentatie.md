---
layout: page-with-side-nav
title: Documentatie StUF-EF
folder_files:
  - title: Ef0315
    path: documenten/Ef0315.zip
    group: 315
    versie: 3.15
    status: Onbekend
    omschrijving: Behoort bij eFormulieren 1.5
  - title: Ef0312
    path: documenten/Ef0312.zip
    group: 312
    versie: 3.12
    status: Onbekend
    omschrijving: Behoort bij eFormulieren 1.4
---
# Documentatie

## StUF-EF 3.15

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 315 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

## StUF-EF 3.12

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 312 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
