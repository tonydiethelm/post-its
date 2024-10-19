# post-its
post it sticky notes


## Purpose:
I like organizing my thoughts with post it notes. I want to replicate that with an online app. 


## How It Works:
- Back End is noSQL database. We'll use Redis. 
	- {name:text, notes: [note0, note1, note2]}, with notes being an object {postion: [x,y], text:text}. 
	- Do I want to iterate through arrays? Or just use key indexing? 
- Load a page with a text box. 
	- Type a name into the text box, it pulls that object from Redis and loads it into state.
	- State refresh reloads page, shows all the post it notes in that object. 
	
We need to be able to select a note and delete it. 
We need to be able to make a new note. Add a "+" button on the page. 

We need styling to make them look like post it notes. 
