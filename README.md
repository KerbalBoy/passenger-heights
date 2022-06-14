# Passenger heights

## Explanation

When an entity rides another in Minecraft, the rider sits a certain, undocumented distance above the mount. This table will help you to figure out what that exact amount is. To get the height of the rider, simply do `mount.getY() + rider.myOffset + mount.passengerOffset`. Greater explanation can be found here. (to be added)

These values have been retrieved from 1.19 NMS source code, and so may not be up-to-date with newer versions.

## Entities

| Entity                               | myOffset              | passengerOffset |
|:------------------------------------:|:---------------------:|:---------------:|
| Allay                                | 0.0                   | default<sup>[1](#1)</sup>         |
| Area potion                          | 0.0                   | default         |
| Armour stand<sup>[2](#2)</sup>       | 0.1<sup>[3](#3)</sup> | default         |
| Arrow                                | 0.0                   | default         |
| Axolotl                              | 0.14                  | default         |
| Baby donkey                          | 0.14                  | 0.3125          |
| Baby hoglin                          | 0.0                   | 0.5             |
| Baby llama                           | 0.14                  | 0.561           |
| Baby mule                            | 0.14                  | 0.35            |
| Baby piglin                          | -0.05                 | default         |
| Baby piglin brute                    | -0.05                 | default         |
| Baby skeleton horse                  | 0.14                  | 0.4125          |
| Baby trader llama                    | 0.14                  | 0.45125         |
| Baby zoglin                          | 0.0                   | 0.5             |
| Baby zombie                          | 0.0                   | default         |
| Baby zombie pigman                   | -0.05                 | default         |
| Bat                                  | 0.0                   | default         |
| Bee                                  | 0.14                  | default         |
| Blaze                                | 0.0                   | default         |
| Boat                                 | 0.0                   | -0.1            |
| Cat                                  | 0.14                  | default         |
| Cave spider                          | 0.0                   | default         |
| Boat                                 | 0.0                   | default         |
| Chicken                              | 0.14                  | default         |
| Cod                                  | 0.0                   | default         |
| Cow                                  | 0.14                  | default         |
| Creeper                              | 0.0                   | default         |
| Dolphin                              | 0.0                   | default         |
| Donkey                               | 0.14                  | 0.875           |
| Dragon fireball                      | 0.0                   | default         |
| Drowned                              | 0.0                   | default         |
| Egg                                  | 0.0                   | default         |
| Elder guardian                       | 0.0                   | default         |
| End crystal                          | 0.0                   | default         |
| Ender dragon                         | 0.0                   | default         |
| Enderpearl                           | 0.0                   | default         |
| Enderman                             | 0.0                   | default         |
| Endermite                            | 0.1                   | default         |
| Evoker                               | -0.45                 | default         |
| Evoker fangs                         | 0.0                   | default         |
| Experience bottle                    | 0.0                   | default         |
| Experience orb                       | 0.0                   | default         |
| Eye of ender                         | 0.0                   | default         |
| Falling block                        | 0.0                   | default         |
| Fireball                             | 0.0                   | default         |
| Firework rocket                      | 0.0                   | default         |
| Fox                                  | 0.14                  | default         |
| Frog                                 | 0.14                  | default         |
| Ghast                                | 0.0                   | default         |
| Giant                                | 0.0                   | default         |
| Glow squid                           | 0.0                   | default         |
| Goat                                 | 0.14                  | default         |
| Guardian                             | 0.0                   | default         |
| Hoglin                               | 0.14                  | 1.25            |
| Horse                                | 0.14                  | default         |
| Husk                                 | 0.0                   | default         |
| Illusioner                           | -0.45                 | default         |
| Iron golem                           | 0.0                   | default         |
| Item                                 | 0.0                   | default         |
| Item frame                           | 0.0                   | default         |
| Lead                                 | 0.0                   | default         |
| Llama                                | 0.14                  | 1.122           |
| Magma cube                           | 0.0                   | default         |
| Marker<sup>[2](#2)</sup>             | 0.0                   | default         |
| Minecart                             | 0.0                   | 0.0             |
| Mooshroom                            | 0.14                  | default         |
| Mule                                 | 0.14                  | 0.95            |
| Ocelot                               | 0.14                  | default         |
| Panda                                | 0.14                  | default         |
| Parrot                               | 0.14                  | default         |
| Phantom                              | 0.0                   | default         |
| Pig                                  | 0.14                  | default         |
| Piglin                               | -0.45                 | 1.794           |
| Piglin brute                         | -0.45                 | default         |
| Pillager                             | -0.45                 | default         |
| Player                               | -0.35                 | default         |
| Polar bear                           | 0.14                  | default         |
| Potion                               | 0.0                   | default         |
| Pufferfish                           | 0.0                   | default         |
| Rabbit                               | 0.14                  | default         |
| Ravager                              | -0.45                 | 2.1             |
| Salmon                               | 0.0                   | default         |
| Sheep                                | 0.14                  | default         |
| Shulker                              | 0.0<sup>[4](#4)</sup> | default         |
| Shulker bullet                       | 0.0                   | default         |
| Silverfish                           | 0.1                   | default         |
| Skeleton                             | -0.6                  | default         |
| Skeleton horse                       | 0.14                  | 1.0125          |
| Slime                                | 0.0                   | default<sup>[5](#5)</sup> |
| Small armour stand<sup>[2](#2)</sup> | 0.1<sup>[3](#3)</sup> | default         |
| Small fireball                       | 0.0                   | default         |
| Snow golem                           | 0.0                   | default         |
| Snowball                             | 0.0                   | default         |
| Spider                               | 0.0                   | 0.45            |
| Squid                                | 0.0                   | default         |
| Stray                                | -0.6                  | default         |
| Strider                              | 0.14                  | ¯\\_(ツ)\_/¯<sup>[6](#6)</sup> |
| Tadpole                              | 0.0                   | default         |
| TNT                                  | 0.0                   | default         |
| Trader llama                         | 0.14                  | 1.1525          |
| Trident                              | 0.0                   | default         |
| Tropical fish                        | 0.0                   | default         |
| Turtle                               | 0.14                  | default         |
| Vex                                  | 0.0                   | default         |
| Villager                             | 0.0                   | default         |
| Vindicator                           | -0.45                 | default         |
| Wandering trader                     | 0.0                   | default         |
| Warden                               | 0.0                   | default         |
| Witch                                | -0.45                 | default         |
| Wither                               | 0.0                   | default         |
| Wither skeleton                      | -0.6                  | default         |
| Wither skull                         | 0.0                   | default         |
| Wolf                                 | 0.14                  | default         |
| Zoglin                               | 0.0                   | 1.25            |
| Zombie                               | -0.45                 | default         |
| Zombie horse                         | 0.14                  | default         |
| Zombie villager                      | 0.0                   | default         |
| Zombie pigman                        | -0.45                 | default         |

## Notes
<a name="1">[1](#1)</a>: The `default` passengerOffset value equals `entity.height * 0.75`

<a name="2">[2](#2)</a>: If `!isMarker() && !isSmall()`, use the armour stand data. If `!isMarker() && isSmall()`, use the small armour stand data. If `isMarker()`, use the marker data. 

<a name="3">[3](#3)</a>: This is a lie. The actual myOffset is `0.1000000014901161`.

<a name="4">[4](#4)</a>: If the shulker not riding a boat or minecart, the myOffset is `0.0`. If the shulker is riding a boat, the myOffset is `0.1875 - boat.passengerOffset`. If the shulker is riding a minecart, the myOffset is `0.1875 - minecart.passengerOffset`.

<a name="5">[5](#5)</a>: Although slimes still follow the `default` rule for passengerOffset, their height can obviously be changed. The actual passengerOffset equals `slime.getSize() * 0.51 * 0.75`.

<a name="6">[6](#6)</a>: The passengerOffset seems to be based off the strider's current animation. If you can explain how this works, let me know. The relevant code is as follows: 
```    
public double getPassengersRidingOffset() {
    float f = Math.min(0.25F, this.animationSpeed);
    float f1 = this.animationPosition;
    return (double)this.getBbHeight() - 0.19 + (double)(0.12F * Mth.cos(f1 * 1.5F) * 2.0F * f);
}
```
