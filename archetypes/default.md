---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
slug: {{ replace .TranslationBaseName "_" "-" | urlize }}
date: {{ .Date }}
draft: true
include_math: false
include_mermaid: false
categories: ["General"]
tags: []
---
