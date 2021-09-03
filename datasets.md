---
title: Datasets
layout: datasets
filename: datasets.md
---
## Datasets
We overview the datasets released through NLB (thus far only those in NLB'21). Technical details and the
dataset itself are provided in the linked DANDI repository and the associated paper. In NLB'21, we
release a collection of four datasets spanning a variety of tasks and brain areas. Though in our
benchmark we are only evaluating a specific set of metrics for each dataset, we encourage the use of
these datasets beyond the scope of our current competition.

<hr>

{%- for dataset in site.data.datasets -%}
<div markdown="1">
### {{ dataset.title }}
</div>

<div style="margin-bottom: 1em;">
    <div style="padding-left: 1em; border-left: 2px solid rgb(195, 195, 195)">
        <div>
            {{- dataset.dandi | markdownify -}}
        </div>
        <div style="margin-top: -1.2em">
            <a href="{{ dataset.notebook }}">Demo Notebook</a>
        </div>
    </div>
    <img src="{{ dataset.image }}" alt="{{ dataset.title }} Schematic"/>
    {{- dataset.text | markdownify -}}
</div>
{%- endfor -%}
