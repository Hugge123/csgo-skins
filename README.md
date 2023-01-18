# csgo-skins
An api with all csgo skins, inspect links and cases


## End Points
## Get all CS:GO cases incluing names, ids and images of each case.
> /cases
```
[
   {
      "name":"Chroma 2 Case",
      "img":"https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsUFJ5KBFZv668FFAuhqSaKWtEu43mxtbbk6b1a77Twm4Iu8Yl3bCU9Imii1Xt80M5MmD7JZjVLFH-6VnQJQ/256fx256f",
      "id":"chroma-2-case"
   },
   {
      "name":"Chroma 3 Case",
      "img":"https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsUFJ5KBFZv668FFYynaSdJGhE74y0wNWIw_OlNuvXkDpSuZQmi--SrN-h3gey-Uo6YWmlIoCLMlhplhFFvwI/256fx256f",
      "id":"chroma-3-case"
   }
.
.
.

```

## Get the contents of each case using their respective id
>/case/[CASE-ID]

```
[
   {
      "name":"Chroma 2 Case",
      "img":"https://steamcommunity-a.akamaihd.net/economy/image/-9a81dlWLwJ2UUGcVs_nsVtzdOEdtWwKGZZLQHTxDZ7I56KU0Zwwo4NUX4oFJZEHLbXU5A1PIYQNqhpOSV-fRPasw8rsUFJ5KBFZv668FFAuhqSaKWtEu43mxtbbk6b1a77Twm4Iu8Yl3bCU9Imii1Xt80M5MmD7JZjVLFH-6VnQJQ/256fx256f"
   },
   {
      "name":"M4A1-S | Hyper Beast",
      "img":"https://steamcdn-a.akamaihd.net/apps/730/icons/econ/default_generated/weapon_m4a1_silencer_cu_m4a1_hyper_beast_light_large.31850937661935a062d5f6faf5a1f02fdb90b861.png",
      "inspect":"steam://rungame/730/76561202255233023/+csgo_econ_action_preview%20M630885829284582097A7014837343D432491715123175296",
      "type":"Covert"
   },
   {
      "name":"MAC-10 | Neon Rider",
      "img":"https://steamcdn-a.akamaihd.net/apps/730/icons/econ/default_generated/weapon_mac10_cu_mac10_neonrider_light_large.4ba82cf2ba2d9fdc694d707b563421bbcc20b174.png",
      "inspect":"steam://rungame/730/76561202255233023/+csgo_econ_action_preview%20M192910765530833031A7015353865D16738789378120206055",
      "type":"Covert"
   }
.
.
.
```

