# The Porthole™

## Adventure
[Chapter 1 -- Camp Behal](chapter01.md)  
[Chapter 2 -- The Herb Cave](chapter02.md)  
[Chapter 3 -- Back to Behal](chapter03.md)  
[Chapter 4 -- The First Oasis](chapter04.md)  
[Chapter 5 -- Into the Sandstorm](chapter05.md)  
[Chapter 6 -- The Porthole](chapter06.md)

## Players
<table><tr>
  {% for player in site.data.players %}
    <td><a href="https://www.dndbeyond.com/characters/{{ player.dndbeyond }}">
    <img src="{{ player.avatar }}"/><br>
    {{ player.name }}</a></td>  
  {% endfor %}
</tr></table>

## NPCs
<table><tr>
  {% for npc in site.data.npcs %}
    {% assign loopindex = forloop.index | modulo: 4 %}
    <td align="top" markdown="span">![{{ npc.nickname }}]({{ npc.avatar }})  
    {{ npc.name }}</td>
    {% if loopindex == 0 %}
      </tr><tr>
    {% endif %}
  {% endfor %}
</tr></table>
