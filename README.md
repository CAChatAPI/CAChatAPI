The github of the CA chat api.


```python
from CAC import ChatApp

APP_ID = "MY_APP"
ROOM_ID = "MY_ROOM"
USER_NAME = "DEV"

app = ChatApp(APP_ID)
room = app.ChatRoom(ROOM_ID)

print("latest: " + room.gm())
print("yours: " + room.pm(USER_NAME, "hi!"))
print("all: " + room.gam())
```
<!---
CAChatAPI/CAChatAPI is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
