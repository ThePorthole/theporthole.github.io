# The Porthole™

## Players
<table><tr>
  {% for player in site.data.players %}
  <a href="https://www.dndbeyond.com/characters/{{ player.dndbeyond }}">
    <td markdown="span">![{{ player.nickname }}]({{ player.avatar }})  
      {{ player.name }}</td>
  </a>
  {% endfor %}
</tr></table>

## NPCs
<table><tr>
  {% for npc in site.data.npcs %}
  <td markdown="span">![{{ npc.nickname }}]({{ npc.avatar }})  
    {{ npc.name }}</td>
{% endfor %}
</tr></table>
