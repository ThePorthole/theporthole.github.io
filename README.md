# The Porthole™

## Players
<table>
  <tr>
    {% for player in site.data.players %}
        <td markdown="span">![{{ player.nickname }}]({{ player.avatar }})  
      {{ player.name }}</td>
    {% endfor %}
  </tr>
</table>

## NPCs
<table>
  <tr>
    {% for npc in site.data.npcs %}
        <td markdown="span">![{{ npc.nickname }}]({{ npc.avatar }})  
      {{ npc.name }}</td>
    {% endfor %}
  </tr>
</table>
