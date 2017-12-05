# Install webview tile

## iOS
* Use iTunes to install custom tile on iPhone
* Connect phone to computer and open up iTunes 
* Select phone icon and *Apps* on the left side menu

![select_phone_itunes]

* Under *File Sharing* select moduware 
* Put tile files in folder named same as tile id. 
    * Tile id uses reverse domain notation as following entity format: "namespace".**tile**."name" - where **tile** is a requiered type: 
    * See this example of folder structure for LED RGB example, nexpaq.**tile**.example-led-rgb
    * Tile folder MUST contain "manifest.json", "icon.svg" and "index.html"
    
* Drag and drop folder with tile to moduware documents
![itunes_drag_and_drop]

## Android

* Connect phone to computer
* Use *File Manager* or *Android File Transfer* (for Mac OS)
* Create *nexpaq* directory on phone's hard drive
* Create folder *tile* and a subfolder for specific tile. 
    * Subfolder tile uses reverse domain notation as following entity format: "namespace".**tile**."name" - where **tile** is a requiered type   
    * See this example of folder structure for LED RGB example, nexpaq.**tile**.example-led-rgb
    
    ![tile_folder_stucture]
    
* Copy *tiles* folder to nexpaq folder

![tiles_MacOS]
![Tiles_Win]

* Restart moduware after installing customized tiles 

[tiles_MacOS]:https://github.com/nexpaq/webview-tile-template/blob/master/images/tiles_MacOS.JPG
[Tiles_Win]:https://github.com/nexpaq/webview-tile-template/blob/master/images/Tiles_Win.JPG
[tile_folder_stucture]:https://github.com/nexpaq/webview-tile-template/blob/master/images/tile_folder_stucture.jpg
[select_phone_itunes]:images/select_phone_in_itunes.png
[itunes_drag_and_drop]:images/itunes_drag_and_drop.png
