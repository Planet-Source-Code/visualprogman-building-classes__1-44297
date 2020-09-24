<div align="center">

## Building Classes


</div>

### Description

Learning the right way to build classes and collection of a class.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[VisualProgman](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/visualprogman.md)
**Level**          |Intermediate
**User Rating**    |3.3 (13 globes from 4 users)
**Compatibility**  |VB 6\.0
**Category**       |[Object Oriented Programming \(OOP\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/object-oriented-programming-oop__1-47.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/visualprogman-building-classes__1-44297/archive/master.zip)





### Source Code

<p>Ok, I just have to thank Microsoft for about 20 hours of research but I ran across these three articles in the MSDN that really shed light on a problem I recently ran into.</p>
<p>I was building a collection of a class in another class and basically wanted to access the information the same way Microsoft does. The simplest example I can think of is the ADODB.Fields relationship compared to the ADODB.Field. ADODB.Fields is really a collection of ADODB.Field.</p><p>In Building the classes I ran across a very interesting problem in trying to add information to the collection class. </p><p>Finally I discovered a bug in VB which I thought was undocumented until in a very obscure area of the MSDN. Actually found the solution. I'm referring to 3 examples in the MSDN "The House of Straw", The House of Sticks" and "The House of Bricks".</p><p>
Once going thru these three examples it has shed some real light on the subject and the answer to the problem.</p>
<p>The House of Straw at:</p>
<p>
http://MSDN.microsoft.com/library/default.asp?url=/library/en-us/vbcon98/html/vbconpubliccollectionexamplethehouseofstraw.asp</p>
<p>The House of Sticks at:</p>
<p>http://MSDN.microsoft.com/library/default.asp?url=/library/en-us/vbcon98/html/vbconprivatecollectionexamplethehouseofsticks.asp</p>
<p>
The House of Bricks at:</p>
<p>http://MSDN.microsoft.com/library/default.asp?url=/library/en-us/vbcon98/html/vbconcreatingyourownclasscollectionthehouseofbricks.asp</p>
<p>
My problem was cured when I entered the -4 in The House of Bricks!</p><p>
Beginners and Intermediates please take the time to do the samples. I guarantee you will be amazed. Man, things just when off in my head wishing I new this a long time ago.</p><p>
My big question is why hasn't Microsoft fixed this???</p><p>
I hope this helps everyone the way it helped me!</p>

