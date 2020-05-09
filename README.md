
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="134" height="20"><linearGradient id="s" x2="0" y2="100%"><stop offset="0" stop-color="#bbb" stop-opacity=".1"/><stop offset="1" stop-opacity=".1"/></linearGradient><clipPath id="r"><rect width="134" height="20" rx="3" fill="#fff"/></clipPath><g clip-path="url(#r)"><rect width="61" height="20" fill="#555"/><rect x="61" width="73" height="20" fill="#007ec6"/><rect width="134" height="20" fill="url(#s)"/></g><g fill="#fff" text-anchor="middle" font-family="Verdana,Geneva,DejaVu Sans,sans-serif" text-rendering="geometricPrecision" font-size="110"><text x="315" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="510">mindorks</text><text x="315" y="140" transform="scale(.1)" textLength="510">mindorks</text><text x="965" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)" textLength="630">opensource</text><text x="965" y="140" transform="scale(.1)" textLength="630">opensource</text></g></svg>
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
