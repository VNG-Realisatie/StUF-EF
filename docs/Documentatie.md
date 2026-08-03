---
layout: page-with-side-nav
title: Documentatie StUF-EF
folder_files:
  - title: Ef0315 (zip)
    path: documenten/Ef0315.zip
    group: 315
    versie: 3.15
    status: Onbekend
    omschrijving: Behoort bij eFormulieren 1.5
    datum: 20131119
  - title: Ef0312 (zip)
    path: documenten/Ef0312.zip
    group: 312
    versie: 3.12
    status: Onbekend
    omschrijving: Behoort bij eFormulieren 1.4
    datum: 20130717
---
# Documentatie

### <span style="color:red">In het kader van de verdere ontwikkeling van de gemeentelijke informatievoorziening richting API-standaarden heeft VNG Realisatie in 2025 een landelijke inventarisatie uitgevoerd. Op basis van de inventarisatie is het koppelvlak StUF-EF aangemerkt als buiten scope voor verdere doorontwikkeling. Zie [hier](https://www.gemmaonline.nl/wiki/Uitkomsten_inventarisatie_StUF-koppelvlakken?mtm_campaign=nieuwsbrief&mtm_kwd=q2_2026) het daarover op 13 mei 2026 op GEMMA Online geplaatste bericht.</span><br/>
### <span style="color:red">T.b.v. de bestaande gebruikers van deze standaard handhaven we deze site.</span>
<br/>
## StUF-EF 3.15

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
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
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>

## StUF-EF 3.12

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
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
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>
