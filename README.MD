# THANK YOU HIFU
Huge shoutout and thank you to HIFU, his void fiend mod helped me immensely to understand which methods were which. As a novice having a reference from somebody else made this INFINITELY easier, endless thanks to HIFU  
## Design Philosophy
Void Fiend feel way to clunky and "floaty", especially early run he just feels terrible. My goal for this mod was to make him far quicker, snappier, and more consistent. I know his theme is supposed to be wild and hectic, but it's just not fun to play.  

## Compatibility
Probably not compatible with other mods that change void fiends abilities, idk for sure I didn't really test it. But just assume stuff will break  

## Primary changes
Corrupted drown is a little too strong, especially early run, nerfing the damage and proc coefficient helps level it out, worse in the early run, still great late run.
* Corrupted Drown  
    * Base damage reduced 2000% --> 1500%
    * Proc coefficient reduced 5 --> 3

## Secondary changes
Honestly I think flood for the most part is fine. Might make some changes down the road. But for now I'm leaving it as is

## Tresspass changes
Tresspass sucks SO BAD especially early run, these changes aim to make it feel much better mobility and consistency wise. These changes are only for the uncorrupted trespass, corrupted is just fine imo

* Changed trajectory ~2 units forward, 2 units up --> ~3.2 units forward .8 units up
* Base charges 1 --> 2
* Base cooldown 5s --> 8s
* Animation time(at base) ~1s --> .5s
* Corrupted tresspass unchanged  
![alt text bigger wiggly](https://github.com/VVitchh/VoidFiendRework/blob/main/images/vanillaTresspass.gif?raw=true) ![Alt text big wiggly](https://github.com/VVitchh/VoidFiendRework/blob/main/images/moddedTresspass.gif?raw=true)

## Suppress
Suppress takes so long, and feels very clunky. Speeding it up lets you dance around while having much more control over corruption levels  

**Uncorrupted:**
* Corruption loss 25% --> 10%
* Healing 25% --> 10%
* Animation time 1s --> .4s  

**Corrupted:**
* Health loss 25% --> 20%
* Corruption gain 25% --> 20%
* Animation time 1s --> .8s
* Base Charges 2 --> 3  
![This is an alt text.](https://github.com/VVitchh/VoidFiendRework/blob/main/images/originalSuppress.gif?raw=true) ![This is an alt](https://github.com/VVitchh/VoidFiendRework/blob/main/images/moddedSupress.gif?raw=true) 

## Passive changes
The main idea to just make the gameplay loop more consistent. Instead of big jumps here and there,  should fill up at a similar pace early run to late run
* Corruption per void item 2% --> 0%
    * Getting to 13 void items and just infinitely healing is dumb, itll always reset to 0
* Each void item increases charge rate by 2%
* Corruption per crit 2% --> 0
* Corruption change per heal -100 --> -50
* Corruption change per damage 100 --> 50
* Transition animation 1s --> .4s
    * Real talk why is the vanilla animation so damn long  


## To-do list / possible changes 
* Rewrite to make all the values configurable 
* Change flood to be higher speed, less damage, idk play with some values there
* Refactor code, im aware my code is complete garbage, acknowledging it absolves me of all wrongdoing 
