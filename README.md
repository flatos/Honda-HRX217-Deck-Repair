# Honda HRX217 Plastic Deck Repair
![Graph](img/trimetric.png)

A description of my repair of a Honda HRX217VLA lawnmower with extensive cracking of the plastic deck.

Includes a downloadable 3D model of the plastic ring I designed to reinforce the damaged area of the deck.

> [!Caution]
> The procedure described here worked for me, and the 3D models are available to download for free.\
> But use the contents of this site at your own risk!
> Review the [disclaimer](#disclaimer) at the end of this page.




## Description


![Graph](img/pre_repair.png)


As seen in this photo, the mower had extensive cracking around the central opening of the deck. 
Some of the cracks had propagated several inches across the deck. 
One of the motor mounts had mostly broken away.

My initial inclination was to try repairing the damage with epoxy (e.g. JB Weld), with steel or aluminum strips or plates as reinforcement.
That probably would have worked, although I had concerns about mechanical strength and rigidity.

Instead, I designed a plastic ring that fits exactly over the damaged region of the deck. It's printed in carbon-fiber-reinforced nylon. 
It helps minimize the amount of expensive epoxy required, and holds everything in proper alignment while the epoxy cures.

Printed with `eSun ePA-CF` filament, the cost to produce the part is around $7.50.



![Graph](img/top_cad.png)
![Graph](img/bot_cad.png)

![Graph](img/top.png)
![Graph](img/bot.png)





# Disclaimer
aed ef sef sff


## Contact
ac8p@proton.me





## Construction

![Graph](img/Explode.png)

| | Qty | Desc | Source |
| :---: | :---: | --- | --- |
| 1 | 20in | 1" PVC pipe, Sch 40 | Home Depot, etc.  $2.96 |
| 2 | 2 | Reel clamp | Reel_Clamp.STL |
| 3 | 2 | PVC Male Adapter, MNPT x Socket, 1 in | Zoro G5275094 $0.67 |
| 4 | 1 | Orbit 57461 1" FPT Jar Top Automatic Sprinkler Valve | Amazon $16.48 |
| 5 | 2in | 1" PVC pipe, Sch 40 |  |
| 6 | 1 | Connector clamp | Connector_Clamp.STL |
| 7 | 1 | GASHER 1/8" NPT Tank Valve, Brass | Amazon $6.95 (pkg of 2) |
| 8 | 1 | PVC Reducing Bushing, Spigot x Socket, 2 in x 1 in Pipe Size | Zoro G5278752 $1.45 |
| 9 | 1 | PVC Coupling, Socket x Socket, 2 in | Zoro G5276433 $2.25 |
| 10 | 24in | 2" PVC pipe, Sch 40 | Home Depot, etc.  $4.94 |
| 11 | 1 | PVC Cap, Socket, 2 in Pipe Size | Zoro G5275225 $1.49 |


Assemble PVC components with the appropriate primer and cement. I used `Weld-On 15900 Twin Pack 780 PVC Regular-Bodied Plumbing Solvent Cement and Purple Plumbing Primer` (Amazon $8.34).

Use yellow Teflon tape on threaded connections. e.g. `Eastman 1/2 Inch x 260 Inch Teflon Pipe Thread for Gas Lines, 4 mil` (Amazon $2.20).


![Graph](img/Main.png)

I used TE CPC connectors only because I had some on hand -- use something cheaper...

![Graph](img/Control.png)

I have a 19.2V cordless drill battery pack that I pressed into service. Standard 0.25" quick-connect terminals will fit the battery's terminals. 
I added a pair of inline fuses (under the heat shrink) to prevent accidental damage... The control box contains only a momentary toggle switch for firing.






## Projectile ("Spud")

![Graph](img/Proj_Assembly.png)
![Graph](img/Proj_Explode.png)

| | Qty | Desc | Source |
| :---: | :---: | --- | --- |
| 1 | 2 | End cap | End_Cap_v3a.STL or End_Cap_v4.STL |
| 2 | 2.5in | 1/2" PVC pipe, Sch 40 | Home Depot, etc.  $1.56 / 24in |

I attached the end caps using self-tapping screws to allow experimenting with additional weight.\
I haven't found this to be necessary, though; the basic 0.7oz spud seems to work fine.

Material cost for each projectile is around $0.25, so you can afford to lose a few in the trees....

The end caps feature a loop to tie the fishing line to without any additional hardware.


## Usage

The unit as described here worked perfectly to launch a line over an approximately 55ft tall tree, using a 50 PSI charge. I haven't done any performance testing beyond that.

I loaded the reel with 15lb monofilament line (`Walmart, $2.42 for 500 yards`) and launched the line over the tree. I then pulled over some sisal (?) twine, 
and finally used the twine to pull the 3/16" Dacron antenna rope.

Additional weight could easily be added to the spuds. They're very light (0.7oz) and might benefit from some added mass, although I haven't tried this.

Many of the designers of similar projects state that modifying the valve for pneumatic triggering gives a noticeable performance improvement (see links below). 
I haven't tried this; electrical activation was easier and worked well enough for my purposes. 

One drawback of this design is that the 3d-printed end caps on the spuds can shatter if they collide hard with an obstacle. Print a couple extra!

## References

Thanks to these previous designers:

[Utah Valley ARC pneumatic launcher](https://noji.com/hamradio/pdf-ppt/noji/Noji-Article-Antenna-Launcher.pdf)

[K4ICY Antenna Launcher](http://www.k4icy.com/launcher.html)

[AE1S](http://blog.kotarak.net/2011/04/say-hello-to-my-little-friend.html)

[K8BLO](https://www.qsl.net/k8blo/launchers.html)

[WS6X](https://www.ws6x.com/squirrel.htm)

[Pneumatic Antenna Launching Systems](http://www.antennalaunchers.com/antlaunching.html)




