---
title: "Recent Projects"
---

{{ with .Page.Resources.ByType "image" }}
    <ul>
    {{ range . }}
    <li>{{ .Permalink }}</li>
    {{ end }}
    </ul>
{{ end }}
