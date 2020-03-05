## Startujemy

TESTTESTTESTTESTTESTTESTTESTTESTTESTTESTTESTTEST

Wszystko jest w budowie lub w fazie planów. Czasem jest tylko pomysł i nie ma nawet planów. 

Mamy zakładke [KONTAKT]({$ link kontakt.md $}) gdyby ktos chciał bardzo coś wysłać.

*Koniecznie zaglądnij [TUTAJ]({$ link procent.md $}) - jest nam to bardzo potrzebne!*

Strona na razie w postaci prostego bloga. Tu są posty/aktualności:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

