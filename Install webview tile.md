# Install webview tile

## iOS
* Use iTunes to install custom tile on iPhone
* Connect phone to computer and open up iTunes 
* Select phone icon and *Apps* on the left side menu

![select_phone_itunes]

* Under *File Sharing* select moduware 
* Put tile files in folder named same as tile id. 
    * Tile id uses reverse domain notation as following entity format: "namespace".**tile**."name" - where **tile** is a requiered type
    * See this example of folder structure for LED tile, nexpaq.**tile**.led
    ![tile_file_structure]
    * Tile folder MUST contain "manifest.json", "icon.svg" and "index.html"
    
* Drag and drop folder with tile to moduware documents
![itunes_drag_and_drop]

## Android

* Connect phone to computer
* Use *File Manager* or *Android File Transfer* (for Mac OS)
* Create *moduware* directory on phone's hard drive
* Put tile files in folder named same as tile id. 
    * Tile id uses reverse domain notation as following entity format: "namespace".**tile**."name" - where **tile** is a requiered type
    * See this example of folder structure for LED tile, nexpaq.**tile**.led
    ![tile_file_structure]
    * Tile folder MUST contain "manifest.json", "icon.svg" and "index.html"
    
* Copy tile folder into *moduware* folder

![moduware_folder_path_and_structure]

* Restart moduware after installing customized tiles 

[select_phone_itunes]:images/select_phone_in_itunes.png
[itunes_drag_and_drop]:images/itunes_drag_and_drop.png
[tile_file_structure]:images/tile_file_structure.png
[moduware_folder_path_and_structure]:images/moduware_folder_path_and_structure.png
