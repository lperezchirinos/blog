---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/header.jpg
feature_row:
  - image_path: /assets/images/logo.png
    alt: "customizable"
    title: "Lo cotidiano es ciencia"
    excerpt: "La ciencia que vemos en nuestras casas."
    url: "https://cientificaserbias.github.io/blog/categorias/#lo-cotidiano-es-ciencia"
    btn_class: "btn--primary"
    btn_label: "Echa un vistazo"
  - image_path: /assets/images/logo.png
    alt: "fully responsive"
    title: "Viaje al centro de la ciencia"
    excerpt: "Tralla de la buena."
    url: "https://cientificaserbias.github.io/blog/categorias/#viaje-al-centro-de-la-ciencia"
    btn_class: "btn--primary"
    btn_label: "Rómpete la cabeza"
  - image_path: /assets/images/logo.png
    alt: "fully responsive"
    title: "Lo que la ciencia se llevó"
    excerpt: "Aquí hablamos de científicos muertos (o no)."
    url: "https://cientificaserbias.github.io/blog/categorias/#lo-que-la-ciencia-se-llevó"
    btn_class: "btn--primary"
    btn_label: "Habla con los (no) muertos"
  - image_path: /assets/images/logo.png
    alt: "fully responsive"
    title: "Crónica de un científico encerrado"
    excerpt: "Nuestro día a día, con sus luces y sombras."
    url: "https://cientificaserbias.github.io/blog/categorias/#crónica-de-un-científico-encerrado"
    btn_class: "btn--primary"
    btn_label: "Conócenos"   
---
<ul class="social-icons">
  {% if site.data.ui-text[site.locale].follow_label %}
    <strong>{{ site.data.ui-text[site.locale].follow_label }}</strong>
  {% endif %}

  {% if site.author.links %}
    {% for link in site.author.links %}
      {% if link.label and link.url %}
        <a href="{{ link.url }}" rel="nofollow noopener noreferrer"><i class="{{ link.icon | default: 'fas fa-link' }}" aria-hidden="true"></i> {{ link.label }}</a>
      {% endif %}
    {% endfor %}
  {% endif %} 
</ul>

&nbsp; 
&nbsp; 
   <div style="text-align: right;color:#668c99; font-size:0.9em;">"La ciencia, hijo mío, está llena de errores; pero de errores que conviene conocer, porque conducen poco a poco a la verdad."<br>
 <i>Viaje al centro de la tierra</i>, Jules Vernes.</div>
  
&nbsp;  
&nbsp;  
&nbsp;
<html>
<head>
<style>

div.ex2 {
  width: 100%;
  right-padding: 30%;
  left-padding: 30%
  box-sizing: border-box;
}
</style>
</head>
<body>

<div class="ex2">&nbsp;&nbsp;¡Bienvenido al club de las científicas Erbias! Este club está formado un grupo de amigos que provenimos de distintas ramas científicas, con el objetivo común de transmitir nuestra pasión por la ciencia a todo tipo de público. Como no todo en ciencia reluce, además de compartir temas de interés científico, os contaremos cómo es la vida de un investigador y los retos y dificultades que conlleva.<br>
&nbsp;
&nbsp;&nbsp;Y como la ciencia es colaborativa, estaremos siempre encantados de oir vuestras opiniones. ¡No dudéis en sugerirnos temas que sean de vuestro interés! Y si además tú también eres científico y quieres unirte a nosotros o hacernos sugerencias sobre cómo mejorar alguna de nuestras entradas, toda idea será más que bienvenida. ¡Nosotros también queremos aprender!
</div>

</body>
  
&nbsp;
{% include feature_row %}

Todas las imágenes bonitas son obra de [@Chir_ii](https://www.instagram.com/chir_ii/?hl=en), los demás hacemos lo que podemos.


