FileToDataURI
=============

A cross-browser solution to read a local file and provide the base64 encoded content.
See the [example](http://aymkdn.github.com/FileToDataURI/) to know how to use it.

Customization
=============

1. Do the changes you need in the mxml file (Flex);
2. Download the [Flex SDK](https://www.adobe.com/devnet/flex/flex-sdk-download.html);
3. Unzip and open a console;
4. Run the following command:
   $ ./bin/mxmlc FileToDataURI.xmxl

You'll have some warning messages as below:
> Chargement du fichier de configuration D:\flex_sdk_4.6\frameworks\flex-config.xml
> RSL requis :
>  http://fpdownload.adobe.com/pub/swz/flex/4.6.0.23201/framework_4.6.0.23201.swz avec 1 basculement.
>  http://fpdownload.adobe.com/pub/swz/tlf/2.0.0.232/textLayout_2.0.0.232.swz avec 1 basculement.
>  http://fpdownload.adobe.com/pub/swz/flex/4.6.0.23201/spark_4.6.0.23201.swz avec 1 basculement.
>  http://fpdownload.adobe.com/pub/swz/flex/4.6.0.23201/sparkskins_4.6.0.23201.swz avec 1 basculement.
>  http://fpdownload.adobe.com/pub/swz/flex/4.6.0.23201/mx_4.6.0.23201.swz avec 1 basculement.

But it will work and you'll find the *FileToDataURI.swf* file in your working directory.

Note
====

For the first run, it's going to be a bit long to load the swf file. Actually the browser will connect to Adobe to download the swz files above. It's doing it just once, then no more need to download them.