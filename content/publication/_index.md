---
title: SMPL Publications
view: citation
banner:
  caption: 'Overview of SMPL research'
  image: Overview.jpg
---

Overview of our research:
- Macroscopic locomotion strategies and molecular regulation in bacteria
- Collective behavior and swarm intelligence in autonomous motile systems and living organisms
- Interactions between bacteria and biological fluids and their medical applications

## Swimming behavior at phenotype
{{% callout note %}}
Explore our research on bacterial swimming and rheotaxis.
{{% /callout %}}
{{ range where .Site.RegularPages "Section" "publication" }}
  {{ if eq .Params.category "Swimming behavior at phenotype" }}
    {{ partial "publication" . }}
  {{ end }}
{{ end }}

## Mechanobiology of cells
{{% callout note %}}
Studies on the mechanical properties of cells and their interactions.
{{% /callout %}}
{{ range where .Site.RegularPages "Section" "publication" }}
  {{ if eq .Params.category "Mechanobiology of cells" }}
    {{ partial "publication" . }}
  {{ end }}
{{ end }}

## Adaptation at molecular scale
{{% callout note %}}
Research on molecular regulation and adaptation in biological systems.
{{% /callout %}}
{{ range where .Site.RegularPages "Section" "publication" }}
  {{ if eq .Params.category "Adaptation at molecular scale" }}
    {{ partial "publication" . }}
  {{ end }}
{{ end }}

## Statistical physics and phase transition
{{% callout note %}}
Investigations into collective behavior and swarm intelligence.
{{% /callout %}}
{{ range where .Site.RegularPages "Section" "publication" }}
  {{ if eq .Params.category "Statistical physics and phase transition" }}
    {{ partial "publication" . }}
  {{ end }}
{{ end }}

## Hard condensed matter
{{% callout note %}}
Exploring material properties in condensed matter systems.
{{% /callout %}}
{{ range where .Site.RegularPages "Section" "publication" }}
  {{ if eq .Params.category "Hard condensed matter" }}
    {{ partial "publication" . }}
  {{ end }}
{{ end }}