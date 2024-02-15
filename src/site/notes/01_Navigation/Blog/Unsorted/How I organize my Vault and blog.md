---
{"dg-publish":true,"permalink":"/01-navigation/blog/unsorted/how-i-organize-my-vault-and-blog/","title":"How I organize my Vault and blog","tags":["status/working-on"],"noteIcon":"","created":"Monday, December 18th 2023, 7:59:35 pm","updated":"2024-01-03T02:52:30.577+01:00"}
---


You know, I think I finally found a program and a system that works for now that will help me achieve all of my [[01_Navigation/Goals for 2024\|Goals for 2024]]

A general system and workflow for my notes includes using tags, metadata and status notes can be found in the canvas file and for organizing this I've had three core philosophies so far.

1. Rely on links over organization
2. Keep Obsidian as Vanilla as possible
3. Dump before you jump
# Good Design Philosophies when Making an Obsidian Vault
The main purpose is to minimize the amount of variables as little as possible and keep it as vanilla obsidian as possible, whenever they release new features I suppose I start using them as well.

### Tags Are not Good Topic Organizers
The problem with having tags as a note system is that it still does is categorizes them and are not linked in context because [[02-Working on/Atomic Notes/Notes Need to Be Deeply Interlinked and Easily Discoverable\|Notes Need to Be Deeply Interlinked and Easily Discoverable]]. Andy M

By linking notes together directly, not as topic linkers: wikilinks do that within context as I am primarily with Atomic Notes as ad-hoc language shorthands.

Where **atomic notes give contexts to each other,** tags are useful to see the properties of a note; where it belongs and which heirarichal structure it can be found in. **Nested tags give not only a sense of repitition, but also structure through association.**

In my vault and my entire organizing system, I follow Matuschaks idea of "prefering associative ontologies over taxonomical heirarichies" which basically means, link notes by association and relevance instead of trying to sort them into batches.

**Obsidian allows for organization through three modes.**

1. **Folders**: In Obsidian, you can organize your notes using a folder structure, just like you would with traditional files and directories on your computer. Folders are used to group related notes together, helping you maintain a logical and hierarchical organization of your knowledge. You can create folders within Obsidian's file system, move notes between them, and even nest folders to create subcategories. This makes it easy to find and access your notes when you have a large collection of interconnected information.

3. **Tags**: Tags in Obsidian provide a flexible and dynamic way to categorize and connect your notes. You can assign one or more tags to each note, which allows you to organize your notes across different dimensions. For example, you can tag notes with keywords like "project," "research," "personal," or any other relevant category. While most people have a tagging system for this, I prefer to use tags only as a form of "properties" indicator, where it tells me what the note is for. [[01_Navigation/Blog/Unsorted/How I organize my Vault and blog#purpose Types Gives Me an Insight in what They Are for\|How I organize my Vault and blog#purpose Types Gives Me an Insight in what They Are for]]

	1. **Bi-Directional Links**: Bi-directional links are one of the core features that set Obsidian apart from other note-taking applications. They enable a two-way connection between notes. Whenever you mention a note within the text of another note, Obsidian automatically creates a backlink from the mentioned note to the note where the reference was made. This bidirectional linking allows you to establish relationships between ideas, concepts, and notes effortlessly. You can see at a glance which notes are connected to a specific idea and this, in essence is how you navigate this website; non-linearily. Remember, this vault is a language and [[02-Working on/Atomic Notes/notes represent my language\|notes represent my language]].

### How I Use Tags in Obsidian

After year or so after using Obsidian seriously, I realized the problems with using tags to organize notes and writings them by topic instead of links.
These were
1. Surprisingly individual notes were not practical to find using tags, [[02-Working on/Atomic Notes/Notes Need to Be Deeply Interlinked and Easily Discoverable\|linked words and sentences worked way better]].
2. At some point there were too many tags, and it was a massive PITA to use tags instead of it.

In my experience, a better way of organizing notes and writings have been to use tags exclusively as a way to filter for a file's
1. Types

For instance, using:
```
#type/litterature-note, #type/game-note #type/daily-note 
```

has the benefits of allowing me to filter by type. Obviously.


2. Status

```
#status/static #status/working-on #status/moc
```

in regards to the status of a note; whether or not I am actively maintaining it or thinking about it – think of it as a /now page, where the current working notes are tagged for easy reference. For instance static notes are notes that I don't work on that often, working-on notes are quite self evident, but what about MOCS?
* MOC notes allow me to group together notes by association and topic, in a less granular way of it.
	* Using Quick-add, it is possible to define rules for where a new note is posted
		* For instance; If it is a note related to a course, a quick-add command that automatically links it to the relevant MOC for this course, as well as

And regarding whether or not a post is public or not; using the digital garden plugin

Various templates (for instance for a litterature note and so on) are already pre-defined to be published for easy acces, but a benefit with allowing publish-status to be turned on/off on a per-note basis gives me peace of mind just in case I accidentally have something in a "published folder" that is not supposed to be private.

And using a plugin like tag wrangler and that one plugin that assigns common tags to notes in a folder, **it is easy to switch what is public and not**

```
//#dg-publish: true or false
//#dg-home: true or false
```


3. Purpose
Well, this one is obvious too no?

``` 

	#purpose
		#purpose/draft 
		#purpose/essay
		#purpose/personal/job-application
		#purpose/blog-post
```

--–
