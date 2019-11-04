The logo files are included in this repo but if you want to know where they came from and how to get more, this explains it.
 

# Creating custom college logo slack emojis

You can borrow high quality vector-based college logos from ESPN.com to use as your custom Slack emoji. 
Slack recommends using square PNGs no smaller than 128K to create your emoji. That happens to be exactly what ESPN.com uses throughout their site. They're really quite well done. 


## How to find the right logo

This ESPN CFB rankings page has lots of logos on it.
https://www.espn.com/college-football/rankings

Each school's logo file can be accessed directly at predictable, structured URLs. For example, ths is Georgia's logo:  
https://a.espncdn.com/i/teamlogos/ncaa/500/61.png

- `\500\` sets the image width to 500 pixels. 
- Georgia's team ID on ESPN.com is 61 so `61.png` calls UGA's logo.
- Changing the team ID gets another school's logo. If we change it to 201 for example, we get team 201's logo. That's Oklahoma: https://a.espncdn.com/i/teamlogos/ncaa/500/201.png

### Getting differnet image sizes
You can also request some different image sizes by including a width and height parameter from another endpoint: 
https://a.espncdn.com/combiner/i?img=/i/teamlogos/ncaa/500/61.png?transparent=true&w=200&h=200
The `&w=200&h=200` returns an image that's 200x200 pixels.


## FBS logos
Page featuring FBS teams with large, high quality logos:
https://www.espn.com/college-football/teams


## FCS and beyond
Page featuring FCS teams with small, high quality logos. Here they're only 40x40 but you can access the full-sized versions by removing the width and height parameters explained earlier. `&h=40&w=40`
http://www.espn.com/college-football/conferences

There's also _some_ DII and DIII teams but the pickins is slim.  




 

