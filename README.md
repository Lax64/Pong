I manually added the data folder into the repository. When pulling in the project make sure to put the data folder into the bin folder.
If the bin folder does not appear in the project file simply create a new bin folder (it should be spelled "bin" all lower case) and place the data folder inside it.
As well makes sure to open the project generator and add these addons to the project. ofxOpenCv, ofxCv, ofxGui.
To add the ofxCv addon you need to grab it from this github repository, (https://github.com/kylemcdonald/ofxCv).
Doing this should allow the project to work as intended
If you extract the project and you see another folder with the same name as the project, just move it one step back in file explorer and the 2 files should fuse.
To run this project you have to have openFrameworks downloaded on your machine and have it placed in the "myApps" folder
