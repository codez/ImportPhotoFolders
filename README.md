# Import Photo Folders

Import a directory hierarchy as albums into OS X Photos (El Capitan).

Just download `ImportPhotoFolders.applescript`, open it in Script Editor and execute it from there.
You will be asked to select the directories to import.

## Example

Given the following directory structure:

* Pictures/
  * Mountains/
    * Asia/
      * everest.jpg
      * k2.jpg
    * Europe/
      * matterhorn.jpg
  * People/
    * i.jpg
    * mejenny.jpg
  * whatever.jpg

When selecting the `Pictures` directory to import, the following structure will be generated in Photos:

* Pictures/ (folder)
  * Mountains/ (folder)
    * Asia (album)
      * everest.jpg
      * k2.jpg
    * Europe (album)
      * matterhorn.jpg
  * People (album)
    * i.jpg
    * mejenny.jpg
  * Pictures (album)
    * whatever.jpg
