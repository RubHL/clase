---
title: "Csv"
date: 2022-10-03T10:36:16+02:00
draft: false
---

{{ $url := "http }}
{{ $sep := "," }}

{{ range $u, $r :=getCSV $sep $url }}
{{ index $r 5}} <br>
{{end}}