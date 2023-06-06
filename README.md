# palmtop site

### update!! cursor works on neocities for some reason. i checked the console of local file and github and both are 404 when trying to get the images so something funky is happening...

### for API calls we have two options, 1: leave it as a client side site that just querys every reload of the page (possible rate limits?), or 2: we can have a DB (I dont know anything about DBs or a text file that gets updated every 1hr with the api calls and then the site pulls data from the text file to reduce API calls). 1 is easier 2 is more practical.

## to-do:

* Add series on homepage
* Have vol covers of manga with arrows to change volume cover, [bootstrap carousels will be perfect](https://getbootstrap.com/docs/4.0/components/carousel/ "Bootstrap site")
* Members page with discord API fetching the most recent pfp and saving so that if the api is not working we still have old pfp
* maybe get a discord bot to post the series updates e.g. raw uploaded, TL done etc...
* automatic countdown for the estimated chapter release
* add FAQ page
    * 
* [Look into Jekyll](https://jekyllrb.com "Jekyll's Homepage")
* [MD API help](https://api.mangadex.org/docs/guide/get-chapters/ "MD API docs")
* https://api.mangadex.org/chapter?groups%5B%5D=ba1f672b-88f2-427e-9aa8-22c94b43ed58&manga=733fc3ac-deca-444e-bb79-14186e00ccf1&order[readableAt]=desc&limit=1&includes[]=scanlation_group API query to get latest chapter of SH
* https://grafana.com
* SH UUID: 733fc3ac-deca-444e-bb79-14186e00ccf1
* Palmtop UUID: ba1f672b-88f2-427e-9aa8-22c94b43ed58