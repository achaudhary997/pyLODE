{{ concept_scheme }}

{%- if has_collections %}
{{ collections|safe }}
{%- endif %}

{%- if has_concepts %}
{{ concepts|safe }}
{%- endif %}

{{ namespaces|safe }}

## Legend
* Collections: cl
* Concepts: cp
