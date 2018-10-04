# The Porthole™
<ul>
{% for player in site.data.players %}
  <li>
    <a href="https://www.dndbeyond.com/characters/{{ player.dndbeyond }}">
      {{ player.name }}
    </a>
  </li>
{% endfor %}
</ul>

<table>
  <tr>
    {% for player in site.data.players %}
        <td markdown="span">![{{ player.nickname }}]({{ player.avatar }})  
      {{ player.name }}</td>
    {% endfor %}
  </tr>
</table>

## Players
<table>
  <tr>
    <td markdown="span">![M'ggah](https://i.imgur.com/TONBUDzb.png)  
      M'ggah</td>
    <td markdown="span">![Myssa](https://i.imgur.com/GjLqK7tb.png)  
      Myssa</td>
    <td markdown="span">![Smokey](https://i.imgur.com/exed6hMb.png)  
      Smokey</td>
    <td markdown="span">![Tia](https://i.imgur.com/T1BZs5Lb.png)  
      Tia</td>
  </tr>
</table>

## NPCs
<table>
  <tr>
    <td markdown="span">![Procrustes](https://i.imgur.com/BcbX6gBb.jpg)  
     Procrustes</td>
    <td markdown="span">![Belln](https://i.imgur.com/Oe1xNnRb.png)  
     Belln</td>
    <td markdown="span">![Eochaidh](https://i.imgur.com/BK7V1ZOb.png)  
     Eochaidh</td>
  </tr>
</table>
