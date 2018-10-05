# The Porthole™

43

![DS](https://cdn.discordapp.com/avatars/464655068793143296/787ab4f674b7eca0a232c82497ccfa25.webp)

<table><tr>
  <td>1</td>
  <td>2</td>
  <td>3</td>
</tr></table>

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
  <td markdown="span">![{{ npc.nickname }}]({{ npc.avatar }})  
    {{ npc.name }}</td>
{% endfor %}
</tr></table>
