---
layout: iotm

release: October 2020
iotm:
  name: Comprehensive Cartographic Compendium
  img: itemimages/cccbook.gif
  description: "This is a really comprehensive book of maps. Map of the secret alcoves of Guano Junction? Check. Map of the little known back-streets Seaside Town? Check. Directions to each tree in the forest? Check. Seems like handy knowledge for an adventurer."
  type: usable
  power: 0
  added-notes: |
   Cannot be discarded<br>Free pull from Hagnk's
  enchantment: |
   Imparts deep cartographic knowledge
  link: Comprehensive_Cartographic_Compendium
  
things:
# skills
- name: Comprehensive Cartography
  type: passive skill
  notes: Unlocks ambient drops, effects, and exclusive non-combats
  img: itemimages/cccbook.gif
  num: 196
 
- name: Map the Monsters
  type: noncombat skill
  notes: Allows player to locate an opponent of their choosing<br>Usable three times a day
  img: itemimages/cccbook.gif
  num: 7344

- name: Leading Yourself Right to Them
  type: noncombat adventure
  notes: Selection screen for Map the Monsters
  img: itemimages/cccbook.gif
  num: 1435
  
- name: Cellar Knowledge
  type: passive skill
  notes: Automatically uncovers two squares of the Typical Tavern Cellar
  img: itemimages/cccbook.gif
  nolink: 1
  num: 196  

# ambient effects

- name: Cartographically Aware
  type: effect
  notes: +30% Combat Initiative<br>Procs randomly after fights
  img: itemimages/cccbook.gif
  
- name: Cartographically Charged
  type: effect
  notes: Maximum MP +10%<br>Regenerate 3-6 MP per Adventure<br>Procs randomly after fights
  img: itemimages/cccbook.gif
  
- name: Cartographically Rooted
  type: effect
  notes: Maximum HP +20%<br>Regenerate 6-12 HP per Adventure<br>Procs randomly after fights
  img: itemimages/cccbook.gif
  
# exclusive noncombats

- name: Billiards Room Options
  type: noncombat adventure
  notes: Options:<br>&bullet; pool cue noncombat<br>&bullet; pool table noncombat<br>&bullet; chalkdust wraith combat
  img: adventureimages/cccmap.gif
  
- name: The Hidden Junction
  type: noncombat adventure
  notes: Options:<br>&bullet; screambat combat<br>&bullet; ~350 Meat
  img: adventureimages/cccmap.gif
  
- name: Your Neck of the Woods
  type: noncombat adventure
  notes: Options:<br>&bullet; second quest noncombat + 1000 Meat<br>&bullet; third quest noncombat
  img: adventureimages/cccmap.gif
  
- name: ...
  type: ...
  notes: to be continued
  img: itemimages/silenttreatment.gif
  nolink: 1
  
  
published: false
---