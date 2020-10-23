---
layout: default
---
"name","heading","explanation","cssClass","externalStyle","style","background","zoomMtg","docLink","backButton","iCal.title","iCal.start","iCal.end","iCal.tz","pageSettings.visible","pageSettings.hidden","pageSettings.highlight","pageSettings.hideZoomLink","pageSettings.hideItemZoomLink","pageSettings.hideDocLink","pageSettings.hideICalButton","pageSettings.hideBackButton","pageSettings.indexUnclickable","pageSettings.hideHeading","pageSettings.hideExplanation","pageSettings.hideIndex","pageSettings.highlightExplanation","pageSettings.showSearchBar","pageSettings.readonly","pageSettings.showItemNumbers","pageSettings.anonymous","pageSettings.timestamp","pageSettings.hideItems"


{% for member in site.data.ncse1 %}
"{{ member.Title | truncate: 40, ""}}","{{ member.Title }}","<div class='ki-title'>{{ member.Title }}</div><div>{{ member.1Abstract }}</div>","Agenda","","","","","","Back","","","","00:00","true","false","false","false",,"false","false","true",,"false","false","false","false","false","false","true","true","false","false"
{%- endfor -%}