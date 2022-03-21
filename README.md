# Panopto Saver
sometimes the script doesnt run until you manully download the first 1-3 TS files by entering the right urls.

1. Enter a video on panopto.
2. Press Ctrl + Shift + I (or right click, "inspect element")
3. Network => (while video is playing) Right click on ts file.
4. Copy link adress.
5. change file name at the end of the URL, and download 1-3 files.
6. Open console and paste the script.
7. change initial number of "for loop" if needed. 
8. also paste the link adress in the script below the Example line without the last part (001337.ts).
9. run the script
10. after all the files are downloaded and the windows start piling up, close the browser.
11. make sure that there are now double files "000000(1).ts" or unrelated ts files in the folder.
12. run the batch file in the folder.
13. the merged file can be run or converted on VLC player.
