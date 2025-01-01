# UOR Core Documentation
Greetings, Writers!

This is the folder for the collaboration and creation of the UOR Foundation's core documentation.
The papers here will define the Foundation and it's purpose. As well as any other documentation the Foundation desires.

Anyone with access to this folder may and can download the latest version/draft of any .pdf.

Final versions will be marked by the removal of the associated .tex and .pdf from this folder, to a more (not yet identified) secure (protection of final version from changes) and global access (transparency and open) folder.

- Purpose
The purpose of this folder is to use git to manage version control of important documentation...not necessary all documention. 

- Document structure
A single document will have 2 files:

1. [same_filename].tex (input)
2. [same_filename].pdf (output)

The .pdf IS the .tex! ("The files are IN the computer!" -name that movie) 

The author will be "UOR Foundation"
The contributors page will list those who contributed.
Date is TBD...it will be the final version (no more edits!)

- How it works:

LaTeX is a markUP language to generate polished, professional pdfs. It allows for full control of the author in how the context is displayed as a pdf. Full control means bigger learning curve. It also provides a simple and quick way to generate professional pdfs by it's default settings, which gets me started quickly.

When generating the .pdf file, latexpdf or latexmk is the tool used.
This tool generates supporting files like .aux and .fls, for example.
They are useless and only used to create the pdf or for debugging.
They are listed in the .gitignore file in this folder.

In case you need it, how I use this folder via codespace...

- Install

-- Install "LaTeX Workshop" codespace extension by James Yu via the "lego blocks" on the far left panel in codespace.
-- In the terminal
--- sudo apt-get update
--- sudo apt-get install -y texlive texlive-latex-extra latexmk
-- Restart codespace

- Edit a .tex and display it's .pdf

-- Open .tex file to edit
-- Hit the run sidways triangle in right corner of codespace
-- Open .pdf after generated in seperate tab

I am sure there are other ways to install and use, this is what worked for me. Key point, the .tex and .pdf shall always have the same filename and have matching versions.

- Pointers that I tell myself to stay focused
-- when editting .tex it's all about context...focus on the words
-- when reading the .pdf it's all about show...focus on the flow
-- let others tell you what it means...focus on the delivery, quitely wait for critisim (I don't like to disturb your thoughts as you read)

I fully expect rich, robust conversation that these documents will spawn as we work together. The hope is that these conversations will create beautiful, thoughtful, practical documents for guidance and direction.

These discussions will also drive the development of say the wiki or tutorials, who knows. The possiblities are endless, and why these core documents and what they SAY are important. Don't hold back, regardless if you don't write or commit a single word, your vision and intent of UOR matters and will be represented in the CORE documents.

Your collaboration and opinions truly matter, even if others disagree. Full agreement is a path to groupthink and groupthink can be a real danger. I only ask in your disagreements to always treat others kindly and respectfully. I aim at creating a friendly-professional work environment dedicated to the advancement and understanding of the UOR. Disagreement is an opprotunity for greater understanding, it is encouraged...respectfully.

You input via verbally, text, scribbles on a bar napkin, in commits, or hate email is all acceptable to me. My focus is the generation of these important documents that support your intention and vision of the UOR Foundation.

I'm looking forward to you collaboration!

Happy writing!!!

p.s. I posted this in haste, so I appologize for any spelling or grammatical errors. Feel free to submit a change.