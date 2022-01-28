An obsidian vault with minimal plugins, designed for newcomers. 

Get [obsidian from here](https://obsidian.md/).

Start it up, and explore the included 'help' vault to become familiar with the interface and concepts. Then, when you're ready, start using this vault.

When you open this vault for the first time, Obsidian will ask you if you want to turn safe mode off; say 'yes'. (There are one or two community plugins used; 'safe' mode disables community plugins. But these ones are ok.)

By the way, academics - I don't have the zotero citations plugin installed here, but if that's something you want, [this is a very nice walk through of using it that will work with this vault too](https://www.marianamontes.me/post/obsidian-and-zotero/).

If you *do* install the citations plugin, you can dispense with the 'ref' note template here, and in the citations plugin settings (when enabled), you can copy and paste the template below into _its_ note template. Then ctrl + shift + e will let you select a citation and create a new reference note. (See other options from the command pallette, eg, inserting a link in a literature note to the reference it cites)

```
---
title: {{title}}
authors: {{authorString}}
year: {{year}}
---

### Article title: 

{{authorString}}. {{year}}. {{title}}, {{containerTitle}}. {{publisher}}, {{publisherPlace}}.

### Summary & Key Take Aways


### Zotero Notes (if any)

{{note}}


--- 

### Links

[Open In Zotero]({{zoteroSelectURI}})

```
