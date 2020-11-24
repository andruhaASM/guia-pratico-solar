---
layout: page
title: "Primeiros passos"
permalink: /primeiros-passos-solar/
description: "Descubra como realizar ações básicas no SOLAR (login, cadastro de assistido e etc) e o canal de suporte ao usuário."
---

 <div class="home">


   
   <ul class="post-list">
     {%- for post in site.posts -%}
     {% if post.cat == "first_steps" %}
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