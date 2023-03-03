What: This doc is an example of a task. 

First, the task will begin with a yaml block, as shown next.

---
doc_type: task
project: CollaborateObsidianGit (COG)
people: Josh, Don, Linda
start_date: 2023-03-03
due_date: 2023-03-10
owner: Don
customer: Josh
description: Install a LiFePo4 battery system in Sprinter Van.
WHATEVER:    
---

Rationale: If document is in a common data serialization format, it is easy to read into a data base and then read, modify, filter, sort, save and so on.

Common data serialization formats: csv, spreadsheet, json, yaml, xml, and so on. 

Yaml is top candidate now because:

1. Easy to read and write. 

2. Obsidian does not screw up display like it does XML and others. 

Notes:

1. Multiple tasks in same note is possible because yaml is nested.

2. I need to figure out and test multiline input. Yaml can do this, but I've not tried this out in Obsidian to see if it plays nice.   

2. Same approach can be used for messages. 

3. Vim editing of shared vault is what I'm doing.
   a. Some major benefits over Obsidian.
   b. Big drawback: vim is not easy to learn. 

