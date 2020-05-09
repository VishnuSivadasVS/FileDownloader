# FileDownloader
Download a file with on click on a button. How to handle all the header properly so that you can download the file in one click.
## How to use?
First of all download the file FileDownloader.php and place it in your project folder. Now add the file FileDownloader.php to your project file by requiring it.
```
require "FileDownloader.php";
```
Simply create an object for the class FileDownloader.
```
$ob = new FileDownloader();
```
Call the fileDownloaderMain() and pass the file url as its argument. 
```
$ob->fileDownloaderMain($url);
```
## Authors

* **Vishnu Sivadas** - *Developer* - [Website](https://www.vishnusivadas.com/)

Check out my other works [@VishnuSivadasVS](https://github.com/VishnuSivadasVS)
