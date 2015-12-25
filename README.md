Bulk Bing Image Downloader (now with lists of keyword support!)
==========================
This forked version of the Bulk Bing Image Downloader has all of the original, but allows the user to user a list of keywords [including how many images you want to download] instead of manually querying each keyword that get loaded into an infinite loop. Keywords and number of pictures be [attempted] downloaded are seperated by a semi-colon

(Original)*Bulk Bing Image Downloader (BBID)* is downloader which:
- downloads full-size images from bing image search results
- is multithreaded
- is crossplatform
- bypasses bing API
- has option to disable adult content filtering
- is written in python 3.
- uses SSL connection

## Example keywords_list.txt
	cats meowing; 50
	dogs woofing; 10
	potatoes gonna potate; 20

*Do note that the number in the keyword list indicates the number of ATTEMPTED DOWNLOADS, not successfuly downloads*

Usage
=====
    python3 bbid.py [keywords_list.txt] [-o [output directory=./bing]] [--filter] [--no-filter] [-h]
