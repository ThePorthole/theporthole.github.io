# The Porthole™

## Players
<table><tr>
  {% for player in site.data.players %}
    <td><a href="https://www.dndbeyond.com/characters/{{ player.dndbeyond }}">
    <img src="{{ player.avatar }}"/></a></td>  
  {% endfor %}
</tr></table>

## NPCs
<table><tr>
  {% for npc in site.data.npcs %}
  <td markdown="span">![{{ npc.nickname }}]({{ npc.avatar }})  
    {{ npc.name }}</td>
{% endfor %}
</tr></table>
