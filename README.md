# Pupique's Vehicle Rebalance Patch

## Purpose

While the mod's title is self-explanatory, I feel it'd be adequate to provide the specific reasoning behind making this patch.

I've played Rimworld in a multitude of different settings, from starting as a tribal to beginning the game as an industrial-level team, crossing through the many vehicle technology levels. One thing remained constant, however: I felt compelled to rebalance every single vehicle I used. Be it them either being too fast, or too slow, or consuming an inadequate amount of fuel, and most importantly: weak armor for some combat vehicles, which is something that can't be patched by the ingame Vehicle Framework mod config.

### In a Nutshell

**In general**, industrial vehicles will consume more chemfuel, with a few notable exceptions. That's because I felt that you could just roam around and go for medium/long hauls without much concern. Vehicles will also have a harder time traversing difficult terrain while having a boost when traveling on roads, thus increasing the value of settling near roads or of getting mods that allows for building roads.

Also, through testing, I've noticed that vehicles move slowly on the world map despite being much faster in the local one, often losing to a single pawn + horse when traveling in virtually any type of terrain. Therefore, I've set all of them to have their world speeds multiplied by 1.5x to compensate that since vehicles should naturally move faster than horses and that their world speeds should better match their local speeds.

Additionally, the fuel capacity of many vehicles was increased not only to adapt to the higher fuel consumption rates but to also add more benefit to using specialized refueling stations.

**Personal vehicles** have a decent overall, striking a balance between weight-carrying, pawn transportation and fuel efficiency and fuel autonomy. Their fuel autonomy is not their strong suit however, often requiring extra fuel on their cargo if going for long trips.

**Motorcycles** consume much less fuel than average and have an easier time crossing through bad terrain when compared to the other types of vehicles while retaining their single-pawn, low carry capacity restrictions. Like personal vehicles, fuel autonomy isn't one of their qualities.

**Transport vehicles** that either focus on pawn or bulk transportation consume more fuel, have a harder time going through bad terrain (with a few exceptions) and are slower in overall. On the other hand, they have a sizeable fuel tank, being excellent for long hauls for not requiring refueling so often.

**Combat vehicles** are in general slower, especially for tanks, and sometimes have a limited fuel capacity, requiring a more careful management when going for more distant raits. They consume a lot of fuel and some of them had their armor values tweaked[^1].

**Naval vehicles** are slow but reliable transportation methods, especially for the pre-industrial ones to better simulate medieval settings and to raise the relevance of river nodes and coastal locations, providing advantages for settling in such locations.

**Aerial vehicles** consume a lot of fuel but, in return, they will be extremely fast and, since they're aerial, terrain penalty naturally doesn't apply to them. Still, their fuel efficiency is intended to be much lower than that of a regular vehicle traversing on a road.

### Disclaimer

As of now, the only mod packs that have been patched are:
* Vanilla Vehicles Expanded (https://github.com/Vanilla-Expanded/VanillaVehiclesExpanded)[see changes](docs/PATCHES_VVE.md);
* Vanilla Vehicles Expanded - Tier 3 (https://github.com/Vanilla-Expanded/VanillaVehiclesExpanded-Tier3)[see changes](docs/PATCHES_VVET3.md);
* Alpha Vehicles - Neolithic (https://github.com/juanosarg/AlphaVehicles-Neolithic)[see changes](docs/PATCHES_AVN.md);
* Alpha Vehicles - Age of Sail (https://github.com/juanosarg/AlphaVehicles-AgeOfSail)[see changes](docs/PATCHES_AVAOS.md).

I patched these mods because they are the ones I use recurrently in my playthroughs and therefore are the ones I feel more qualified to make adjustments to.

> [!NOTE]
> Since this mod only applies patches that tweak some values, it is safe to both add and remove it mid-game.

> [!NOTE]
> This mod needs to be placed after the previously mentioned ones in the load order. You may have any combination of them active at the same time as the patch will be applied dynamically depending on what you have active.

### License
This mod falls under the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

[^1]: Vanilla armor rates were left as they are. The armor tweaks that this patch applies depend on having Combat Extended enabled. You may apply this patch without CE without any issues, with the only difference being that the Vanilla armor values were left untouched.
