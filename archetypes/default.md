---
date: '{{ .Date }}'
draft: true
comments: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
---
