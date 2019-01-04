---
title: "{{ replace .TranslationBaseName "-" " " | title }}"
slug: {{ replace .TranslationBaseName "_" "-" | urlize }}
date: {{ dateFormat "Jan 2, 2006" "2007-10-04" }}
draft: true
include_math: false
include_mermaid: false
categories: ["General"]
tags: []
---
