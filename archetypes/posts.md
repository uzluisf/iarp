---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
slug: {{ replace .TranslationBaseName "_" "-" | urlize }}
date: {{ .Date }}
draft: true
categories: []
tags: []
---
