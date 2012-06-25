# RailsCasts Episode #361: Facebook Graph API

http://railscasts.com/episodes/361-facebook-graph-api

Requires Ruby 1.9.2 or higher.


### Commands used in Rails console

```
u = User.first
u.facebook.get_object("me")
u.facebook.get_connection("me", "television")
u.facebook.get_object("22934684677")
u.facebook.get_object("TheBigBangTheory")
u.facebook.put_wall_post("testing")
u.facebook.get_connection("me", "permissions")

u = User.last
u.facebook.get_connection("me", "permissions")
u.facebook.put_wall_post("testing")
u.facebook.fql_query("select pic from page where username='amazon' or username='google'")
```
