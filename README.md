# improviz-linux-guide

Improviz is a live coding environment built by Guy John aka Rumblesan. It is available as a stand-alone desktop application and as a web app. It is similar in appearance and functionality to LiveCodeLab but the desktop version extends this functionality by giving the user the option to load their own custom textures, animated gifs, shaders, and 3D models.

![improviz_linux_001](images/improviz_linux_001.jpg)

As with a lot of live coding languages, one of the most difficult barriers to using them is setting up the environment and installing them, especially if you're used to just downloading a file and double-clicking it to install and run it.

In this short tutorial I'll show you how to launch Improviz using the terminal, which will be useful when using Improviz but will also put you in a better position for doing programming and using other live coding tools.

For this particular tutorial I’m using a Ubuntu 20.04 computer, and will be using the default Firefox Browser.

1. Launch your browser and go to [https://improviz.rumblesan.com/](https://improviz.rumblesan.com/) . This is the official website for Improviz and should be your first stop for finding out more about the software.

2. Under the Installation section click on where it says "pre-built binaries". This will take you to the Github site where you can download a version of the software that is compatible for your operating system.

3. As we're using Linux download the one labelled `improviz-nix-0.8.2.tar.gz`. The zip file you download may have a different version number if there have been updates since this video was made, but that’s ok. This will start the download of the software. By default this will download it to your Downloads folder.

4. Open your Home folder and then navigate to the Downloads folder. If you've set a different location for your downloads you should go there instead. In there you'll see the `improviz-nix-0.8.2.tar.gz` file. This is a zip folder containing the software. To unzip it right click on the file and click Extract Here.

    After a short moment a new folder will appear called `improviz-nix-0.8.2`. Inside that folder you’ll see a folder called `improviz-nix`. In that folder you'll see lots of different files, including one called improviz.

    You may be thinking that to run Improviz you would double-click on the improviz file. While this is an option, for Improviz we need to open, or launch, the software from the terminal. This approach has multiple benefits, and for Improviz it will allow us to see an error message when we make mistakes.

5. To open the terminal click on the Activities button in the top-left corner. From there, you can type terminal and press Enter.

    Using the terminal is like navigating your computer but without your mouse and only using text commands. A full explanation of using the terminal is out of the scope of this introduction video, but a few guides are linked at the end of this tutorial.

    By default when you open the terminal you are located in your Home folder. If you type `ls` you can see a list of your files and folders. We need to navigate to the location where you Improviz folder is. The command `cd` allows you to change directory to one you specify. This is similar to double-clicking on a folder icon with your mouse.

6. In the terminal type `cd Downloads`. Now when you type `ls` you'll see a list of the files in that folder.

7. Again in the terminal type `cd improviz-nix-0.8.2` and press Enter. Of course you should substitute this with a different number to correspond with the version of Improviz you downloaded.

8. In that folder type `ls` to see the files and folder. Then type `cd improviz-nix`.

9. Finally, now that you're located in the right folder in the command prompt type `./improviz` to launch Improviz.

10. If you get a white screen appearing in the top-left corner of your screen then you're ready to start learning to use Improviz!

    If you don't you can report an issue to the developer by going to the address below.

    You can also chat visit a forum for livecoding where a community of users may be able to help you.

You're now ready to start using Improviz! There are example files located in the Improviz folder you downloaded which you can learn from, or you can search on the internet to see if there's any upcoming Improviz workshops.
