---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
albumthumb: "{{ .Name }}/{{ .Name }}-01.png"
resources:
- src: "{{ .Name }}/{{ .Name }}-01.png"
---
