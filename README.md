The github of the CA chat api.


```python
from CAC import ChatRoom, InitializeUser

cr = ChatRoom("code from website")
user = InitializeUser(input("Name: "))

print("latest: " + cr.gm())
print("yours: " + cr.pm(user, "hi!"))
```
<!---
CAChatAPI/CAChatAPI is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
