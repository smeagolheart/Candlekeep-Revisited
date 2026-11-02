This mod adds more content to the oft-considered tiresome prologue of the first Baldur’s Gate, adding ‘new’ NPCs, extended dialogue with Gorion and your childhood acquaintances, the option to allow Imoen to join you in your last wandering around Candlekeep, as well as many, many extra scenes, including a starting sequence based on your main character’s class with various starting bonuses.

In essence, this turns the tutorial into a boring section of the game which most people choose to either skip or quickly rush through for some starting experience to a more prolonged experience with moments of friendship, some development of Gorion’s character (interpretations may vary) and overall a more emotional departure that makes the homecoming sweeter. The mod also adds some minor Chapter 6 content which builds off the new connections, though most of the focus is in the prologue.

New content:

– Introduction of the ‘tutorial party members’—Arkanis, Canderous, Deder, Mordaine and Osprey—as new NPCs in Candlekeep’s courtyard, with dialogues and personalities

– Three minor sidequests involving the NPCs

– An experience reward with words of wisdom from Tethtoril if you complete every optional sidequest in Candlekeep, giving you enough experience to level up. (If you don't want it, tell him you don't have the time to listen.)

– Extra dialogue with the NPCs for your reunion with them in Chapter 6

– Improved Arkanis and Deder in the catacomb sequence in Chapter 6, making them stronger, controllable, and expanding their dialogue

– An optional component for an extended starting sequence based on class, paired with extended dialogue with Gorion and an earlier appearance of Ulraunt

– New optional portraits for the aforementioned five NPCs in place of their vanilla portraits

---

## Changes in this fork (smeagolheart)

This fork adds a few quality-of-life changes and two new optional components to the original mod by ArtemiusI.

**Skippable cutscenes (component 0)**

– The Ulraunt scene at the gates can now be skipped with Esc, like the base game's cutscenes. Skipping jumps straight to Gorion's follow-up conversation.

– The extended armored figure (Sarevok) ambush can now be skipped with Esc at any of its scenes, using the base game's own ambush skip, which takes you to the start of Chapter 1.

**New component 5: Extended dialogue with Gorion and Ulraunt**

– Gorion's farewell talk and the earlier appearance of Ulraunt, split out of the Expanded Starting Sequence so they can be installed without it. Requires component 0.

– Component 1 still includes this scene on its own, so components 1 and 5 can't both be installed, and the scene is never added twice.

**New component 6: AI voiced lines**

– Adds voice acting for the lines this mod adds (353 lines). **The voices are AI-generated** and are not by the original author or any voice actor.

– Each sound is attached by matching its line's exact text in dialog.tlk, so it works with whichever components you have installed. Lines from components you haven't installed are skipped, and lines that already have a sound are left alone.

– Install it after any other Candlekeep Revisited components. If you add a component later, reinstall component 6 so the new lines get voiced.

**Two dialogue lines changed so they could be voiced**

– Gorion's "No." and Ulraunt's "Bah!" in the Ulraunt scene are word-for-word the same as lines already in the base game. WeiDU reuses existing strings when the text matches exactly, so these lines would have shared the base game's string and couldn't get their own voice. Each now ends in a trailing space, which makes it a separate line. The space doesn't show in the game.

**Fix: departure stalling when Imoen is in your party**

– On my EET install, choosing to leave Candlekeep with Imoen in the party got stuck after her goodbye: Gorion never walked to the gate and the move outside never happened. Without Imoen it worked normally.

– The cause appears to be that Imoen's goodbye started the departure cutscene herself, while that same cutscene's first step makes her leave the party and the area. Gorion now starts it instead, which is what already happens when Imoen isn't with you.

– I've only confirmed the problem on EET (with other mods installed), so it may not happen on plain BG:EE. The fix is safe either way.
