# esx_irforce_lootdeadcorpse

this is my very first script

it allows specific jobs to loot dead corpse, of course with a cute animation by pressing 'E'.

### Prerequisites

only works with ESX
## Demo
[![Watch the video](https://cdn.discordapp.com/attachments/584460034541617172/631138375189004288/unknown.png)](https://cdn.discordapp.com/attachments/587184003291938817/631087554665381898/IRforCe_Loot_The_Dead_Corpse.mp4
)



## Installing

after download/clone rename the folder from 
```
irforce_lootdeadcorpsee-master
```
to
```
irforce_lootdeadcorpse
```
then goto to the address below and change the jobs name of your liking
```
irforce_lootdeadcorpse/client/main.lua:29
```
just replace the "jobname-here" with the job name you like
for example:
```
if IsControlJustReleased(0, 38) and ( ESX.PlayerData["job"]["name"] == "fbi" or ESX.PlayerData["job"]["name"] == "police" ) then
```
and for the final step put the line below in your server.cfg file
```
start irforce_lootdeadcorpse
```
### forum link
[[Release] [ESX] IRforCe Loot The Dead Corpse](https://forum.fivem.net/t/release-esx-irforce-loot-the-dead-corpse/826653)
## Enjor it🤩
## Contributing

Please read [CONTRIBUTING.md](https://github.com/H0ssein/irforce_lootdeadcorpse/blob/master/CONTRIBUTING.md) for more information.