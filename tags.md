Tags: 
{% for tagitem in site.tags  %} 
  [{{  tagitem[0] }}](#{{ tagitem[0] }}) 
{% endfor %}