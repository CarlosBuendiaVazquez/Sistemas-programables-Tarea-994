---
title: Beige Theme
layout: post
permalink: /beige/
theme: beige
 
slides:
 - title: Slide FKJSANFLKAS
   slide-data: PRUEBA FF
 
     
 - title: Slide 2
   slide-data: This is second slide

   
 - title: Slide 3
   slide-data: This is third slide

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
    
