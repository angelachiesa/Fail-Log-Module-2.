# Fail Log for Module Two
#### July 17 - 23: Module 2 Finding Data
---
##### Previous Mistakes
A few mistakes that I think are important to note was that I completed the blog post wrong. I misunderstand the part of Dillinger and did the post in the software rather than on Word Press. This created a lot of issues as the post was not able to be seen when I submitted the assignment.

Another mistake that I noticed was I tried to format with Dillinger into my fail logs, however it didn’t work. This week, I didn’t make the same mistake and made sure it set it up correctly.

Another comment that was made was how I didn’t expand my relation to the Readings, so this week, I’m explaining in a lot more detail on why I can relate to them and how.

##### Readings
For this week's annotations, we had a few choices on which articles to do our annotations on. I choose to do mine on Seams and Edges: Dreams of Aggregation, Access & Discovery in a Broken World. To summarize, the reading goes over the process of technology and the ability that we have now with these tools to search information at such a large scale. With gadgets such as google and trove, searching has become much simpler than ever before.

Overall, an enjoyable read, I enjoyed it because I could relate to it because whenever I go through text or formats, I always search keys words. These gadgets really do make learning and studying easier and enjoyable in way. I've done work with only going to library and looking through book by book and it is extremely time consuming. Most of my annotations are just comparisons to when I’m searching or using this form of technology. The author also points out the difference between search engines which I've never noted. For example, he talks about Querypic allows you to see different trends in history. To be more specific he makes note about how World War I was known as the Great War, something I've found extremely interesting. This whole time whenever I did history projects or referred to these wars, I relied on google to learn about these times, however at least in my memory, I never came upon it being known as the Great War. It of course makes sense, that it all changed afterwards with the impact of World War II. The article overall just taught me the difference of search engines which I found incredibly useful for the future, and it taught me not just to relay on one. Always thought in my mind not just to relay on one website, but now I know not to just relay on one web searching software.

# Exercise 1: The Dream Case
For Exercise 1, there was two databases, Epigraphic Database Heidelberg and Commwealth War Graves Commission, Find War Dead. Part of the exercise is to search things into both, one being your own surname. Unfortunately, when I tried searching into the  Commwealth War Graves Commission, it wasn’t working properly. When I  search my last name, and the page just refreshes. I'm thinking that there is just no one under my last name, so I'm just going to use the Epigraphic Database for this module. 


Just did a simple search and had to go back to tutorial 1 to remember how to use the Nano text editor. I downloaded the information, made a repository in GitHub. Dragged the file in, added the file into DH box. I pressed so many things that I’m not 100% sure what way I did made it correctly. (correct me if I’m wrong) but what I think I did correctly was type in

**Notes To Remember for Future Purposes**
1.	Download the any excel information
2.	Create a Repository 
a.	Click Initialize this repository with a README
b.	MIT License
3.	Upload File
a.	Drag File from Downloads
4.	Press Download File

DH Box
5.	wget https://github.com/angelachiesa/Number-of-Inscriptions-in-Chronological-Data
a.	Gets the file in
6.	You need to unpack the file
a.	sudo dpkg -i pandoc-1.19.2.1-1-amd64.deb
7.	Press ls, make sure the file Is in there
8.	Now I don’t know if I coned the file or forked it or something, but the file turned blue, I tried a lot of different ways to do this.
9.	But once the file is blue, type in nano and the name of the file
a.	Example nano Spoon-Knife
b.	And you can make changes within that folder
10.	Type whatever you want into nano, go into comman line after the file that you saved.
11.	Download it and than upload and drag that file into git Hub.
12.	Ta da! Only forgot one step, not to bad.



##### Reflection

---
>The search database for Epigraphic was interesting. What I liked about it or at least what I found interesting, was that it even rated the quality of the photo it provides with you of the archeology. I just liked this because it was something that I’ve never seen before.Unfortunately, I don’t know a lot about archelogy, so a bit harder for me to search for specific things.As for the Commonwealth database, that’s something that seems to be a lot more common. However nothing came up. I knew my family fought in both wars, no required deaths that I know of. The site just refreshed when my name did come up, so I just stayed with the first database. One thing that I didn’t understand, was the part of downloading the results? After help on explanation on what to download, I was able to get the results. I did have a lot of trouble trying to do this all from memory mainly because it's not like these commands are
 easy to remember. I basically had to do the whole tutorial from last week again, and rewrote the steps in my own words to keep track of it this time. I played around for a bit and got the turotial however I can't remember how I got one step. These things really do take time, and it's important not to get frustrated.
 
 # Exercise 2: Wget

 
**If I ever want to download an entire website**
 1. mkdir wget-activehistory
 2. wget http://activehistory.ca/papers/
 3. wget -r --no-parent -w 2 --limit-rate=20k http://activehistory.ca/papers/
 
 
 The text files were really rough as it wasn't as clear just like how it mentioned in the exercise.

##### Reflection
-------------
> This exercise was a lot more straightforward. I just followed the steps and everything went smoothly. 

# Exercise 3: TEI
For exercise 3, I was able to download the zip file fine. Notepadd++ was also used for this tutorial

#### More on transformations ### 
_What tags would it be looking for in the xml file? What might it do to your markup? What line would you change in your XML file to get it to point to this stylesheet?_
The tags in SG_transformer.xsl would be looking for newspaper articles. Not quite sure what it would do to my mark up. I think I would change the last line from xsl:stylesheet to xml:stylesheet.

**Notes**
1. <p> is to start a paragraph.
2. </p> is to end a paragraph
3. For claims you use <interp key="reason" n="citation" cert="high" ref="http://www.website.com/webpage.html"> </interp>
4. For places you use <placeName key="Sheffield, United Kingdom" ref="http://tools.wmflabs.org/geohack/geohack.php?pagename=Sheffield&params=53_23_01_N_1_28_01_W_type:city_region:GB""> </placeName>
5. and for names you use <persName key="Last, First" from="YYYY" to="YYYY" role="Occupation" ref="http://www.website.com/webpage.html"> </persName>
**Link for future**
https://via.hypothes.is/http://workbook.craftingdigitalhistory.ca/supporting%20materials/tei/

>Reflection
This exercise went okay however I had trouble setting up the format. I didn't quite understanding the <p> command worked. I thought you had to do it for each paragraph and not for the whole thing total. Was able to complete it in the end and submit it. 


# Exercise 4: APIs
I just generally kept notes to remind me myself for the future.

**Notes**
How to download a text in DHBox
1. type in wget and the URL
- If you want to see the first few sentences, type head, and the file name
- If you want to see the last few sentences, type tail, and the file name
2. To make a copy, type cp __file name__ and __file name__ -backup.txt
3. To see less of the text, 	
less -N stmtn10.txt
4. to delete, sed '2206,2525d' stmtn10.txt > stmtn10-nofooter.txt
- all this does is delete lines from between 2206, 2525d and renames it
5. sed '1,40d' stmtn10-nofooter.txt > stmtn10-trimmed.txt this just trims the header from the file with no header or footer and makes a new file
6. if you want to know how many lines or chracteres the file has, l it's these commands
- wc -l stmtn10-trimmed.txt
- wc -m stmtn10-trimmed.tx
7. To find patterns
- grep -n "giant" stmtn10-trimmed.txt
8. takes out all punctuation and lower/upper case
- tr -d [:punct:] < stmtn10-trimmed.txt > stmtn10-nopunct.txt
9. what we use to convert all of the windows line endings to the LF line endings
- tr -d '\r' < stmtn10-lowercase.txt > stmtn10-lowercaself.txt


**More Notes**
1. To make a new directory - mkdir
- mkdir m2e4
2. To make an empty file for our project - touch
- touch canadiana.sh
3. Open the empty file - nano
- nano canadiana.sh
4. To change permissions on a file - chmod 755
- chmod 755 canadiana.sh
5. to run it - ./canadiana.sh
6. 

**More Notes**
To save work in the history
1. Type history
2. history > dhbox-work-today.html
3. Download file from file manager and add into Git Hub.
-----
>Reflection
For the most part things went smooth. I went back to last weeks to remember how to do some things like saving the history and etc. I'm really starting to know the importance of keeping notes and etc so i'm doing that more. I don't really commit in DH Box much, mostly because it's something that i'm still confused on doing. I'm going to attempt to do that next module involving Dh Box but I do keep track of what i'm doing in the fail logs, and now that I understand the history part, Git Hub can keep track of my commands. Slowly learning!

# Exercise 5: Mining Twitter
Twarc is now installed into DH Box.
**Notes**
To search Twitter's hastags - only last two weeks
twarc search canada150 > search.json
____
>Reflection 
I think this exercise was easiest for me because it was a software I've used before, so it wasn't overwhelming or felt like a challenge. Twitter is familiar, and DH Box is becoming more so. 
# Exercise 6: Using Tesseract to turn a pdf into text
What this exercise contained.
1. install the Tesseract OCR engine into your DHBox
2. download an edition of the Equity
3. install and use pdftk to burst the pdf into 4. individual one-page files
4. install and use imagemagick to convert the pdf into tiff image format
5. use Tesseract to OCR the resulting pages.

>Reflection
I made it to step 4 but for whatever reason, DH Box would not install pdftk. After typing in the command, sudo apt-get undate, it was finally able to get through. I did experience more problems because in the next step I got errors when it comes to extracting the pdf, therefore I couldn't complete exercise 6. I did put in a lot of effort to try and complete.  


## Overall Week
I spent a lot of time doing the exercises and making sure I understood what was happening and finally kept tracking and made better notes. 


