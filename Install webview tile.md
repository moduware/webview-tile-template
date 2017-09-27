# Install webview tile

## iOS
* Use iTunes to install custom tile on iPhone
* Connect phone to computer and open up iTunes 
* Select phone icon and *Apps* on the left side menu

![itunes1]

* Under *File Sharing* select moduware 
* Create a folder *tiles* and a subfolder and a subfolder for specific tile. 
    * Subfolder tile uses reverse domain notation as following entity format: "namespace".**tile**."name" - where **tile** is a requiered type: 
    * See this example of folder structure for LED RGB example, nexpaq.**tile**.example-led-rgb
    
    ![tile_folder_stucture]
    
* Drag and drop *tiles* folder to moduware documents
![itunes2]

## Android

* Connect phone to computer
* Use *File Manager* or *Android File Transfer* (for Mac OS)
* Create *nexpaq* directory on phone's hard drive
* Create folder *tile* and a subfolder for specific tile. 
    * Subfolder tile uses reverse domain notation as following entity format: "namespace".**tile**."name" - where **tile** is a requiered type   
    * See this example of folder structure for LED RGB example, nexpaq.**tile**.example-led-rgb
    
    ![tile_folder_stucture]
  
* Add all webview tile files to the last directory
* Copy *tiles* folder to nexpaq folder

![tiles_MacOS]
![Tiles_Win]

* Restart moduware after installing customized tiles 

[itunes1]:https://github.com/nexpaq/webview-tile-template/blob/master/images/itunes1.JPG
[itunes2]:https://github.com/nexpaq/webview-tile-template/blob/master/images/itunes2.JPG
[tiles_MacOS]:https://github.com/nexpaq/webview-tile-template/blob/master/images/tiles_MacOS.JPG
[Tiles_Win]:https://github.com/nexpaq/webview-tile-template/blob/master/images/Tiles_Win.JPG
[tile_folder_stucture]:https://github.com/nexpaq/webview-tile-template/blob/master/images/tile_folder_stucture.jpg