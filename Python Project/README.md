# Music Player

<p>
The music player is the device for playing MP3 and other digital audio files. The music GUI program application attempts to emulate the physical music player. This program allows you to play songs, music and all music files on your desktop or
laptop. The main goal of this project is to enable users to play music and digital audio files. In order to be attractive to users, the application must have a simple but beautiful user interface. Music Player has options to play, pause and stop. We can have an interface to list the music files available. You can also allow users to list
other digital audio files that are not music. Users are also waiting for the music player. have an interface that displays information about the file being played. Python has libraries that can play audio files, such as: B.Pygame, which allows you to work with media files in just a few lines of code. Recently, music has become popular with this generation. Most software companies develop so many types of players that they can support MP3 files. 
</p>

## Deatails of Project Developed

<p>
The MP3 player is a device for playing and listening to digital audio files, which can be MP3 	files or other audio files. The player was created in Python language. A GUI implementation 	of the application has been developed that is simple and easy to use. The application gives 	the user five options: add a song to a playlist, play the song, pause or resume the song, 	play the previous song, and play the next song. It has a large display area in which the 	playlist is visible. Once a track has been selected and played we can listen to it and view 	details, the song is at the top of the screen. This information includes details about the 	song, such as: B. the name of the song.
</p>

<ul>
<li><b> Tk() </b> is a top level widget that is used to create the main application window in which we will be building our python project.</li>
<li><b> title() </b> method is used to give a name to python mp3 player application which is displayed at the top.
<li><b> mixer.init() </b> is used to initialize the mixer module so that we can use it’s various functions in our application.
<li><b> Listbox()</b> widget is used to create a listbox in which we will store our songs.
<ul>
<li> We have passed various parameters, first is the root specifying that the widget should be placed in the python mp3 player window.</li>
<li> Then, bg is for background color, fg is for foreground color.</li>
<li> selectbackground and selectforeground basically change the background and the foreground color of a particular item upon selecting it.</li>
</ul>
<li><b> grid()</b> widget is a geometry manager which organizes the widgets properly in a grid-based fashion before placing it in the root window. columnspan=9 gives a space of 9 columns to our listbox widget.</li>
<li><b> Button()</b> widget is used to create a button. We want the buttons in our main window so the input root is given. Then the text which will be displayed on the button is specified and at last in the command input a function is given which will be called when the button is clicked.</li>
<li><b> Menu()</b> widget is displayed just under the title bar, it is used to conveniently access various operations. We are going to access Add songs and Delete songs for our playlist, upon clicking addsongs and deletesong functions are called respectively.</li>
</ul>

## Algorithm

<ol>
<li>Import the libraries.</li>
<li>Create an object of the tkinter and Pygame libraries.</li>
<li>Create a window using Tkinter object.</li>
<li>Add buttons that provide different functionalities.</li>
<ul>
<li>Add a song</li>
<li>Play the song</li>
<li>Pause the song</li>
<li>Play previous song</li>
<li>Play next song</li>
 </ul>
<li>Add path from where playlist should be taken.</li>
<li>Add label to display the song’s information.</li>
<li>Display screen will display the details of the entire playlist.</li>
<li>Configure the buttons of play, pause, resume, stop.</li>
</ol>

## Output
![image](https://user-images.githubusercontent.com/53977573/173591639-864e049d-6390-411e-9041-c5712d8d97c7.png)
