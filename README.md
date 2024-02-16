# MITAppInventorNoteTaker-Documentation
(This does not show my work for developing apps or applications, I am just not skilled using the MIT App inventor project.) 
Documentation using the read.me for md for my MIT app inventor project:
Link: https://github.com/KaiKitKobold/Kaia-AI2-Project.git

Project/app overview:


[Further details can also be found in the read.me file.]


The app I’ve created is a Single Screen, Scrollable, Note-taking app, that primarily uses buttons for it’s control flow, but also uses some procedures for Dry code implementation. 


The app also uses Tiny.Db in order to save the files that shows up on memory. 
There are two separate lists into which the Notes are split into, Note names and Note Content (Which contains the note that the user has put it) These lists are then further used for the file name for exporting, and the content for the test inside the txt file that is exported. 


There are around six buttons that are used for importing, add note, refresh note, delete note, export button, and refresh screen all of which do the following things: 


When it is initalised it get the value from tiny.db and adds the contents of the global nists of nameList and contentList 


Add note: sets an state in order for stuff to get added, and adds the content to the corresponding lists, they then stay in memory until they click
Refresh screen: This adds the content that was done in added note, including everything else of the list in order to the list-view component, in order to be selected for future use, and also stores the list inside the database. 
Delete note: Deletes the note from both the database and the list from the memory.
Import: Imports the file, saves it and then places the name as placeholder, and the content as the contents of the file. 
Export: Exports an file to the shared database as an txt file and then uses the name, and the content in order to determine the name and text of the file. 






Hyperlinked list of any resources used:


https://community.appinventor.mit.edu/t/write-to-a-textfile/81977
https://community.appinventor.mit.edu/t/copy-a-txt-file-in-a-list/6260
https://community.appinventor.mit.edu/t/how-to-create-a-list-using-text-file-or-csv-file/14139/9
https://community.appinventor.mit.edu/t/how-to-access-non-media-media-files-on-android-11/54828/3


Summary details of the development process:
It mainly started yesterday. Since submitting this report, I have been busy with my other classes and my Programming Practice Article. My stance on this App does not accurately reflect how I treat programming and software development, I understand everything however making apps through MIT app inventor is frustrating and annoying, debugging is difficult, my brain has a really hard time programming reading and mentally visualising codebases, using visual coding blocks, I preface this by saying I’m not attempting to gain sympathy or attempt to get a higher grade, personally I think what I have is a 40-60%, but definitely not an 0%.


Personally, I was going to initially give up and just focus on redoing my Project Scope for UI/UX, and try to make up the grade with midterms/ the final project, but I decided to just breathe, book tutoring and attempt to try it with an couple of references. 


It didn’t end up great but with a couple of iterations, I think I have something that conceptually makes sense, mind you I could not test out it’s implementation and truly get immersed with the project because of the error that I mentioned in the read.me, so I just have the fundamentals of what it is, however if you asked me to explain it in terms of an traditional codebase, I’d most likely do so, as well as the other topics such as peer/code review and app documentation. It’s just really hard to do so with such a limited resource. 




Summary details of code review:
Since this project is being submitted near the deadline and reading break and since I’m not a social person around campus, it is nearly impossible for me to get someone to test with this. However, I instead will give a synopsis of my code-review of someone else’s work. 


I have decided to look at : https://github.com/nic-dgl104-winter-2024/nazrinzuwair Repository. 


Code Review done: https://github.com/nic-dgl104-winter-2024/nazrinzuwair/commit/b1748a60e1c324cadd4a1ac44dae79bb71daa272


The Code inside doesn't use any procedures, this does mean that the scope of the content wouldn’t be replicable in something much larger than an app. However, the Nazrinzuwair repository is more comparable to a small code snippet and in that regards it fulfills it’s purpose well. 


When testing, I didn’t find any bugs in their app, and their code was responsive, with clear indicators if I inputed right or wrong information (Mind you, I don’t know any of the answers since I’m not a sports fan.) 
In terms of layout, it’s relatively basic but works well, the only gripe I have is that the next question button, and the confirm button are an bit too close together and on smaller screens, would be hard to touch, however, in the grand scheme of things, it’s a small Usability error. 
The code is well-organized and seems to be very procedural in it’s implementation, making it so that if your list of questions or answers contained anything else, it would still work as intended. 


Overall a very basic app, but with stellar implementation. 


