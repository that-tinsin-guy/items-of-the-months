---
layout: iotm

release: December 2020
iotm:
  name: box o' ghosts
  img: itemimages/cghostbox.gif
  description: | 
   The label on this box says "A box of three ghosts". Another label says "Open in case of insufficient holiday cheer". A third label says "This end up". 
  type: usable
  power: 0
  added-notes: |
   Cannot be discarded.
  enchantment: |
   (Contains three familiar hatchlings.)
  link: Box_o'_ghosts
  
things:

# hatchlings
- name: gregarious ghostling
  type: familiar hatchling
  notes: Hatches into Ghost of Crimbo Carols.
  img: itemimages/cghost1.gif
  num: 10649
  
- name: grinning ghostling
  type: familiar hatchling
  notes: Hatches into Ghost of Crimbo Cheer.
  img: itemimages/cghost2.gif
  num: 10650
  
- name: greedy ghostling
  type: familiar hatchling
  notes: Hatches into Ghost of Crimbo Commerce.
  img: itemimages/cghost3.gif
  num: 10651

# familiars
- name: Ghost of Crimbo Carols
  type: familiar
  notes: |
   Increases item drops from monsters<br>
   Casts buffs on you during combat<br>
   Shares XP with the other Crimbo Ghosts
  img: itemimages/cghost_carols.gif
  num: 280

- name: Ghost of Crimbo Cheer
  type: familiar
  notes: |
   Gives you more stats after combat<br>
   Makes it snow in zones you visit<br>
   Shares XP with the other Crimbo Ghosts
  img: itemimages/cghost_cheer.gif
  num: 281
# carol buffs



- name: ...
  type: ...
  notes: to be continued
  img: itemimages/silenttreatment.gif
  nolink: 1
  
  
published: false
---