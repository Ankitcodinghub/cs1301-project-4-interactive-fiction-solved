# cs1301-project-4-interactive-fiction-solved
**TO GET THIS SOLUTION VISIT:** [CS1301 Project 4-Interactive Fiction Solved](https://www.ankitcodinghub.com/product/cs1301-project-4-interactive-fiction-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;54134&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1301 Project 4-Interactive Fiction Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Once upon a time, before the dawn of the Internet as we know it, there lived a forgotten type of computer game called interactive fiction. First written in the late ’70s, these games were sort of a choose-your-own adventure book, but for geeks. These games contain no graphics, just a 2nd person (everybody remembers English class, right?) description of your character, and a box for entering commands. With the birth of the kindle and other Internet enabled e-readers, these games are experiencing something of a rebirth, as their screens are a perfect match for these games.

Photo from: http://www.indieretronews.com/2018/01/the-pawn-classic-text-adventure-by.html

To play one for yourself, go to <u><a href="https://eblong.com/zarf/zweb/dreamhold/">https://eblong.com/zarf/zweb/dreamhold/</a></u>

&nbsp;

Your project is to create an interactive fiction. In this game, you will navigate a map (moving east, west, north, south when possible).&nbsp; In each “room” of the map, the game will print a description of the room to the screen.&nbsp; As you navigate through the map, you will be looking for a light to light up the dark rooms, a key to open a treasure chest, and a chest (that contains the treasure!).&nbsp; Once you have found the key, you can open the chest.&nbsp; While going through the map, you must watch out for the deadly grue! To help you get started on the game, a couple of classes have been written for you.&nbsp; You only need to make the guts of the game, called the engine. You will find Map.java, Room.java, Lamp.java, Key.java, and Chest.java on the course website.&nbsp; Some of these classes are completely finished and others are just skeletons (containing comments and method signatures).

Begin by taking a quick a look at the Map class, which is completely implemented for you (<strong>do not modify the Map class, just know how to use it</strong>). In this game, a map is a square of size NxN where each cell contains a room. Each room contains a description of the room and possibly a few other items. You call the getRoom(X,Y) to retrieve the Room object for a given square. The first number (X) gives the row and the second (Y) gives the column. The starting room is at (0,0).

To the right is a picture of a general map.&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; … &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; n

<table width="0">
<tbody>
<tr>
<td width="39">X</td>
<td width="38"></td>
<td width="39"></td>
<td width="38"></td>
<td width="38"></td>
</tr>
<tr>
<td width="39"></td>
<td width="38"></td>
<td width="39"></td>
<td width="38"></td>
<td width="38"></td>
</tr>
<tr>
<td width="39"></td>
<td width="38">&nbsp;O</td>
<td width="39"></td>
<td width="38"></td>
<td width="38"></td>
</tr>
<tr>
<td width="39"></td>
<td width="38"></td>
<td width="39"></td>
<td width="38"></td>
<td width="38"></td>
</tr>
<tr>
<td width="39"></td>
<td width="38"></td>
<td width="39"></td>
<td width="38"></td>
<td width="38"></td>
</tr>
</tbody>
</table>
Note that the map can be of any size.&nbsp; To &nbsp;&nbsp;0 clarify the X and Y positions, we have 1 marked the map at position (2,1) with an 2 O. In this cell, we would say that the X … value is 2 and the Y value is 1.&nbsp;&nbsp; n

While debugging your code, you can run the program in “simple map” mode where the map contains only a single room (see below). This is useful in debugging because no one wants to walk through a huge map only to find that the final command doesn’t work. When you have tested your code and want to play the entire game, set the simpleMap variable to false for a larger map.&nbsp;&nbsp; The larger map we have provided is of size 5×5.

Illustration of Map when simpleMap = true

0

<table width="0">
<tbody>
<tr>
<td width="34">X</td>
</tr>
</tbody>
</table>
0

<strong><em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;</em></strong>

Now take a look at the Room class. This class is implemented for you as well. It contains a large number of methods for you to use during the game. As you can see, there are no setters, only getters. This means that for the most part you cannot modify any Room objects you receive. The exceptions are the clearKey() and clearLamp() methods that modify two of the room’s sub objects. Note: these methods allow you to modify a Room object. <strong>You should never modify the Room.java code</strong>. You’ll see down below when you need to call these methods. If a room does not have a specific sub-object (key, lamp), its variable will be set to null. You will need to test for this condition to see if a room has a sub-object or not. <em>The description of the interface for this class is given at the end of this pdf.</em>

Now, take a look at the Key class, it is written for you. <strong>You do NOT need to update anything in the Key.java file.</strong> The Key class only has one method: public void use(Chest onChest). Calling this method simply calls the unlock method on the given chest.<em> The description of the interface for this class is given at the end of this pdf.</em>

&nbsp;

<h1>Program Requirements – General Algorithm</h1>
You should <strong>NOT modify <em>Room.java</em> or <em>Map.java or Key.java</em></strong> to get your game working. Your project will be tested with our own versions of these two files, so any modifications you make could result in your project not compiling or not working correctly.

Also – <strong>you should never create new Key or new Chest objects.&nbsp; This is done already in the preexisting code. So, if you add the words “new Key()” or “new Chest()”, you will have logical errors in your code.</strong>

<ol>
<li>You should start your work by implementing the Chest class (a skeleton is provided for you). It needs to store whether it is locked or not, a String describing the contents, and which key it was locked with. The method stubs for this class are provided with comments, be sure to implement them the way they are described. You should not add any more methods to this class.</li>
<li>Next, implement the Lamp class (the class definition is provided for you), it only needs to store whether it is lit or not. Follow the rules of encapsulation/information hiding, and prevent any other class from accessing or modifying your instance variables directly.</li>
<li>Then, create a player class in a file called <strong>java</strong>. No skeleton is provided for you, you must create it from scratch. You’re responsible for adding instance methods and variables. A player object will represent the user playing the game, and thus needs to store which map square they are currently on (integer x and y coordinates), the lamp and key. You should create instance class type variables for the lamp and key, and if they happen to be null, the player does NOT currently have them (same is true for the Room objects as well). Be sure to follow encapsulation rules here too. You do not need to initialize the lamp and key instance variables, as they will default to null.&nbsp; When the player collects the lamp and the key, you will call setLamp and setKey to set these variables.</li>
<li>Once these are done, create a class called <strong>Adventure</strong> and write the <strong>main method</strong> of your program in it (remember that the class that contains the main method is the one that you run). The first thing to do in main is to create a Player object and set its starting coordinates to (0,0). Also, you will need to create a new Map object. The idea in the Adventure class is that you loop repeatedly until the player dies (attacked by grue – see below) or finds the treasure (opens chest – see below). Every time the player moves, update the player’s position and get the appropriate Room object from the map. Using this object, display the appropriate text to the user based on what command they type in. A list of commands is given below.&nbsp; Ignore case on the user input.</li>
</ol>
<ul>
<li>GET LAMP – If the lamp is present in the current room (there is a method in the Room class (i.e. getLamp()) that allows you to check this. Note the method’s return type and assign the return value accordingly), this transfers the lamp from</li>
</ul>
the room to the player. Be sure to clear the lamp from the room afterwards. Print “OK” if successful, or “No lamp present” if not. Note: that you can find the lamp in a dark room.

<ul>
<li>LIGHT LAMP – If the player has the lamp, this sets it to lit. Print “OK” if successful, or “You don’t have the lamp to light” if the player doesn’t have the lamp.</li>
<li>NORTH, SOUTH, EAST, WEST – If the current room (prior to the move) isDark(), AND the player doesn’t have the lamp OR they have the lamp but the lamp is not lit, the player is eaten by a grue and the game is over. (see below for an example). Otherwise, move the user North one square (-1 x), South one square (+1 x), East one square (+1 y), or West one square (-1 y). See table below to understand x and y in the context of the map. Once you move into a new room, you should print out its description, so the user doesn’t have to type LOOK every time. Be sure to check the current room object to see if the given direction is valid. If not, print (“Can’t go that way”). If the room (after the move) isDark() AND the player does not have the lamp OR the lamp is not lit, then instead of printing the description, tell them: “It is pitch black, you can’t see anything. You may be eaten by a grue!”. (see below for an example)</li>
<li>LOOK –If the room isDark() and the player does not have the lamp or the lamp is not lit, then instead of printing the description, tell them: “It is pitch black, you can’t see anything. You may be eaten by a grue!”. (see below for an example). Otherwise, this prints the description of the current room object, as well as any objects that are in the room. You should also print which exits from the room are valid.</li>
</ul>
<ol>
<li>If the lamp is present in the room, print “There is an old oil lamp here that was made long ago” after you have printed out the room description. ii. If the key is present in the room, print “You see the outline of a key on a dusty shelf that’s covered in dust.” after you have printed out the room description.</li>
</ol>
iii. If the chest is present in the room, print “There is a large, wooden, massive, oaken chest here with the word “CHEST” carved into it” after you have printed out the room description.

<ul>
<li>GET KEY – If the key is present in the room, this transfers the key to the user’s inventory. Be sure to clear the key from the room afterwards. Print “OK” if successful, “No key present” if not.</li>
<li>OPEN CHEST – If the chest is present in the room and is unlocked, then this should print out the chest’s contents and end the game. If the chest is locked, print “The chest is locked”. If the chest is not present in the room, print “No chest present”.</li>
<li>UNLOCK CHEST – If the user has the key, call the use() method with the chest object to unlock it, then print “OK”. If the user doesn’t have the key, print “Need a key to do any unlocking!”. If the chest is not present, print “No chest to unlock”.</li>
<li>(anything else) – Just print “I’m sorry I don’t know how to do that.”, and reprompt the user to allow the user to enter another command. The user should be able to continue playing after an invalid command is inputted, and the game should continue normally after an invalid command.&nbsp; The program should not crash or end abruptly if the user inputs an invalid command.</li>
</ul>
<ol start="5">
<li>When your program starts, print out the following text: Welcome to UGA Adventures: Episode I</li>
</ol>
The Adventure of the Cave of Redundancy Adventure By: (Your name)
