# manyjitsis
Many Jitsis for you to choose: pick the one you want from the list on the left. To edit that list, change this part in the `index.html` file:

```html
<div id="rooms">
  <p class="selected" data-room="ManyJitsisMainRoom">Main room</p>
  <p data-room="ManyJitsisRoomOne">Room One</p>
  <p data-room="ManyJitsisRoomTwo">Room Two</p>
  <p data-room="ManyJitsisRoomThree">Room Three</p>
  <p data-room="ManyJitsisRoomFour">Room Four</p>
</div>
```

The text inside the `<p></p>` element is the displayed room name. The `data-room` attribute contains the name of the room as it will be created in jisti. For example, the main room will be `https://meet.jit.si/ManyJitsisMainRoom`. Use creative names here to avoid collisions!
