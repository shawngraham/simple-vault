---
title: Getting Started with Obsidian
date: 2022-01-26
tags: introduction, help
---

(best viewed with preview turned on; the table of contents can be viewed by clicking the sidepanel at right and clicking on the toc button)

# What is this?

This is a folder of individual text files using the markdown extension & conventions. When used in combination with the [obsidian.md](https://obsidian.md) interface which permits and encourages interlinkages of files, like a personal wiki, this folder becomes a knowledge base for your research and learning. It can become not just a _repository_ of what you've learned, but a _generator_ for new insights.

A short video that shows the basics of Obsidian (not by SG):
[https://www.youtube.com/watch?v=QgbLb6QCK88](https://www.youtube.com/watch?v=QgbLb6QCK88)

A video showing just how powerful Obsidian can be for your notetaking can be found at [' How to turn your notes into published articles and books using the Obsidian app with Eleanor Konik'](https://www.youtube.com/watch?v=nO5N_x2so0g).

If you click on the 'open vault' button, you can load/open the default vault that comes with Obsidian, and which will show you other aspects of Obsidian's functionality. You can have more than one vault open at a time.

# Basic use

## Record your process
- make a daily note (there's a button in the toolbar) every day to record what you're doing/thinking. Dump into that note thoughts, problems, issues, inspirations. You can always parse it out into better notes later, and it's good to keep track of things

- when you're working on a a technical tutorial or some kind of digital project, create a new note with ctrl +n, then from the command palette (ctrl + p) select 'Templates: insert from template' and select the process note template to help keep track of your thoughts. **confusingly, there is also a command 'Templater: insert from template'** The command with the 's' inserts the simple template; the one with the 'r' inserts complex templates (the difference between simple and complex is that the latter contain actual code)

## Notes on your thinking
- record the summary of the literature you are reading by making a new note, then selecting the literature note template
- make notes as you read or think about the content of the course. One strategy is to make a new note for a unique thought/idea - make a new note, and insert the atomic note template

## Explore how things connect
- periodically, explore and re-read your notes with an eye to creating links between them.  Type `[[` and `]]` to find connections between your notes, and to interlink them (you can also highlight a word, and then type the square brackets). As you type, Obsidian searches through your notes to find notes by title or content. (NB: one square bracket `[like this]` is the first part of making an _external_ link in your note, `[like this](https://example.com)`).

## Organize if you want but you don't have to
- You **can** create folders to file your materials, but you don't have to. You **might** create a folder called 'inbox' for when you've started a note or idea that you want to come back to mull over, and whatever other folders you want to store the various notes you've created.


##  Graph View
I find the graph view to be useful to understand how my notes are linking up, and to find notes that are otherwise orphans. You can visualize by tags or particular search queries (by defining 'Groups' under the cogwheel icon on the graph; you can filter in particular ways too. 

##  Pinning notes
You can have as many notes open as you want; you can pin certain notes to always be visible; you can rearrange the workspace to how you like it.

## From notes to drafts

- Build up 'over view notes' on a topic or idea by creating a new note; use the search function, the graph visualiation, or other kinds of plugins (look up 'journey' for instance in the community plugins section) to find threads of related ideas. Add these links to your over view note. Then, if you wish, you can place a `!` in front of the links, which will _embed_ the contents of the note, the block, or the media into your note (for embedding blocks of text from a note, see the next section on using the `^` to anchor the text). Such notes can be copied or exported to other writing systems (the pandoc plugin for Obsidian will turn the note into html or Word .doc format, for instance) 


# Slightly More Complex Use
- Open the command palette to find the complete list of commands you can run. These include:
	- inserting templates into new notes, for consistency (make a new note, click the cursor in there, then insert template) "templates: insert template"
	- grabbing hypothesis annotations (via the Templater) command (make a new note, click the cursor in there, then insert template)  "templater: insert templates". Note, **templater**. Also available from command bar under the relevant icon 
	- selecting a block of text to turn into a new note, connected to the original note "note composer: extract text"

- Use the backlinks and outgoing links panel, and the graph panel, to see how your notes interconnect, and to find _potential_ connections

- When you search for notes, you can copy the search results into a _new_ note; the results will all be links.

- If you install the pandoc plugin for obsidian (after first installing [pandoc](https://pandoc.org/installing.html) on your computer) you can export notes into a .docx file formatted for Word etc by selecting pandoc from the command pallette. 
	- If you don't, that's ok too: just hit the preview button and then copy and paste into word.

## Embedding (transcluding) text

You can create notes (new files) in Obsidian that _embed_ notes, paragraphs, or headings from _other_ notes. In this way, you can build up drafts, outlines, and more complex pieces of writing that you can then export to Word and so on. This features is called _transclusion_ and you do this by putting an exclamation point in front of the `[[` to link to your note; then, with the link created, insert a `^` at the end of the note name (but before the closing `]]` and obsidian will show you the various blocks of text _within_ that note. Click on the one you want, and Obsidian will create the link. With preview on, you'll now see the embedded text.


##  Create notes from your hypothesis annotations
- Create a new note, then insert the hypothesis template. ('insert template**r**' in the command pallette)
- When you run the hypothesis templater command in a new note for the first time, Obsidian will first prompt you for your Hypothesis user token. You find that at your Hypothesis user page. Once you give that to Obsidian (which it will keep in a file here in your vault for you, so you only ever have to do it the first time), you will be prompted  for the url or date for the resource you annotated; it will then grab those annotations as separate notes. 
- there are community plugins to allow you to extract annotations made on local pdfs; the best of these at the moment seems to be 'PDF Highlights', which you can find under settings, browse community plugins. 

##  Refactoring your notes

Sometimes, a note will become too large, containing too many ideas. Under settings, core plugins, there is a setting for 'Note Composer'. Turn this on.

Then, in a note, you can highlight the materials you want to extract; hit ctrl + p to bring up the command pallette, and search for 'note composer'; your various options will appear. If you select 'extract', Obsidian will make a new note from the material and leave a link to the new note in the old one.

For instance, this current 'getting started' note is really long now, and contains a lot of different information. Why not break it up into separate notes, and leave this current note as a kind of table of contents with links? Highlight this _entire note_, and then extract it into separate notes by headings!

(There are tools to do this sort of thing via community plugins that can be tailored to your own particular workflow, offering more customizability than the core plugin, by the way.)

# The Point

Obsidian works as a personal knowledge base; seeing your notes develop and beging to interlink - and being able to search those patterns - supercharges your note taking abilities and the value of your reading. With time, you'll start to see connections and patterns in your thoughts. You're building up a **personal knowledge base** that becomes more valuable the more you use it. 

I have a vault with over 400 notes in it. When I get an idea, I search my vault for relevant notes, and then embed them into a new document. I write around the existing notes, and then export to word for final polishing, citations. This accelerates my writing considerably, and helps me pull my research together into coherent form.

# Going Further

There are any number of plugins that can enhance Obsidian, from citations and notes pulled from Zotero & pdf readers, to calendars, to using natural language processing to find notes with similar ideas that are otherwise unconnected.

**Readwise** has created a (paid) plugin to allow export of notes from its service to Obsidian; this is helpful if you use ereaders and so on. They are also working on a reader app that will similarly connect to Obsidian and so you should keep an eye on it. 

There is a **kanban** plugin that lets you create a board with kanban cards that can be rearranged, added to, etc, to keep track of projects. I use a very simple arrangement with three cards: to do, doing, done. Under each card, I list tasks. These can be checked off. 

I have a vault with an 'ocr templater' script that extracts text from images into a new note that you're welcome to adapt/adopt [link here](https://github.com/shawngraham/obsidian-student-starter-vault).

One I quite like is called '**Journey**' which finds paths between notes, and then pastes the links for that path into a new note (from which you can then develop a longer form of writing).

Speaking of writing, the **Longform** plugin lets you designate a folder in your vault as the container for your writing project. The notes you then create in that folder become the sections of your work (longform calls them 'scenes'); you can reorder them by moving them  around. These sections/scenes/notes work like regular obsidian notes, so you can embed other notes or sections of notes as appropriate. The whole thing can then be compiled and exported. If this all sounds very much like Scrivener, then you'd be right: Scrivener is a direct inspiration.

There are plugins that will allow you to export a bibliography from Zotero and to create notes from those Zotero items; this can be connected with workflows for extracting notes from pdfs (with things like Zotfile; I don't know how this will work with the new Zotero beta with integral pdf annotation). These workflows are more complex than I will discuss here; suffice to say you can find a lot of information [here](https://forum.obsidian.md/t/zotero-zotfile-mdnotes-obsidian-dataview-workflow/15536).

Another very useful one is called 'dataview'.  **With dataview installed**, you can add a code block in a note and have Obsidian compile dynamic information based on your notes. The following code block (if dataview is on) creates a view of the most recently edited notes (especially useful if you're using folders to also try to create some sort of structure):

```dataview
TABLE dateformat(file.mtime, "dd.MM.yyyy - HH:mm") AS "Last modified"
FROM ""
SORT file.mtime DESC
LIMIT 25
```

This code block will gather notes together that have been tagged with in-line metadata, ie `projects::[[]]` is used to tag a note eg `projects::[[secret-project]]`

```dataview
table type
where contains(projects, [[secret-project]])
```


# Final Thoughts
Don't get too hung up on plugins. There are *many* plugins, and playing with them, customizing them, can eat up a lot of your energy. Just get comfortable with the idea of making literature notes and then atomic notes, before going too much deeper into the weeds. The point is to make a structure to think in; finding connections should be pleasurable.

# Acknowledgement

The structure of this vault and some of its note templates is patterned after the approach Andrew Roddick uses with his anthropology students at McMaster University.
