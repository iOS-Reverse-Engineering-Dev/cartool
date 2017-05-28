cartool
=======

Export images from OS X / iOS .car CoreUI archives. Very rough code, probably tons wrong with it, but still useful.
Extract all assets, including images and files `.ipa` in an application.

## Usage
1.Download an application from App Store  -->  `Show In Finder`, you'll see a `.ipa` file --> right-clicked it, and unzip it to a folder, then enter PayLoad directory  -->  right-clicked XX.app file , select `Show Package Contents`  -->  find out `Assets.car` file  --> copy it to a custom folder you create.

2.Edit Scheme -->  Run  -->  Arguments  -->   Arguments Passed On Launch  -->  add two paths ,first is the path of `Assets.car`，second is the path of extracting all files to a custom folder 

3.Build it. You'll see all files was extracted from `Assets.car`.
