---
layout: page
title: "Perguntas Frequentes"
permalink: /perguntas-frequentes-solar/
description: "Tire aqui as dúvidas mais comuns sobre o SOLAR."
---

 <div class="home">


   
   <ul class="post-list">
     {%- for post in site.posts -%}
     {% if post.cat == "faq" %}
     <li>
       <h3><a class="post-link" href="{{ post.permalink | relative_url }}">
           {{ post.title }}
         </a></h3>
           {{ post.excerpt }}
    </li>
     {% endif %}
     {%- endfor -%}
   </ul>




</div>