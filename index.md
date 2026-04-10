---
title: オンラインでホストされる手順
permalink: index.html
layout: home
---

このページには、[Microsoft Learn](https://learn.microsoft.com) の Microsoft スキル習得コース「[MS-4004: Microsoft 365 Copilot を使って従業員を強化するユース ケース](https://learn.microsoft.com/en-us/training/courses/ms-4004)」に関連付けられているラボ演習の一覧が表示されます。

<hr>

## ラボ

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" | where_exp:"page", "page.lab.title" | sort: "url" -%}
{% assign current_module = "" -%}
{% for activity in labs -%}
{% assign relative_url = activity.url | remove: "/Instructions/Labs/" -%}
{% assign module_folder = relative_url | split: "/" | first -%}
{% if module_folder != current_module -%}
{% assign current_module = module_folder -%}
{% assign module_num = module_folder | slice: 0, 3 -%}
{% assign module_desc = module_folder | slice: 4, 200 | replace: "-", " " | capitalize -%}
{% assign total_duration = 0 -%}
{% for p in labs -%}
{% assign p_rel = p.url | remove: "/Instructions/Labs/" -%}
{% assign p_mod = p_rel | split: "/" | first -%}
{% if p_mod == module_folder -%}
{% assign d = p.lab.duration | split: " " | first | plus: 0 -%}
{% assign total_duration = total_duration | plus: d -%}
{% endif -%}
{% endfor %}

### {{ module_num }}: {{ module_desc }} ({{ total_duration }} 分)

| ラボ | Level | Duration |
| --- | --- | --- |
{% endif -%}
| [{{ activity.lab.title }}{% if activity.lab.type %} - {{ activity.lab.type }}{% endif %}]({{ site.github.url }}{{ activity.url }}) | {{ activity.lab.level }} | {{ activity.lab.duration }} |
{% endfor %}
