https://github.com/OceanSky/htaccess/
# htaccess
.htaccess Boilerplate - Make your website faster and more secure.

===================================
.htaccess BoilerPlate Instructions
===================================

Trick out your website!  Gain control of how your web server behaves.  Speed up web page load times and hinder potential security threats.  You can also redirect visitors, password protects directories, create custom error pages, and so much more!

Requirements:
-You have have a web hosting provider and domain name (obviously)
-Your web server must actually use and be set to utilitze the .htaccess file (most Linux servers, including apache)
-You must have password/login access to your server's root directory (use FTP, cpanel, or similar)
NOTE:  .htaccess is a 'HIDDEN FILE' so you must have permission to 'Show Hidden Files' and edit them.

WARNING:
A misconfigured .htaccess file can result in a 500 Internal Servor Error -- your website can stop working!
Even a single misplaced character can cause a huge problem.  So ALWAYS BACKUP your original .htaccess file before you start.  

Steps:
1. Log into your web server's public_html (or equivelent) directory (use or web hosting control panel or FTP software -- Dreamweaver is perfect for this.)
2. Download and/or otherwise BACKUP YOUR CURRENT .htaccess file
3. Download (and unzip) '.htaccess BoilerPlate'
4. Upload the '.htaccess.txt' file to the appropriate directory on your server (usually /public_html).
5. Open a web browser and load your website's homepage.
6. Open the '.htaccess.txt' file in your text editor/FTP client software.
7. Add a new line to the top or bottom or the .htaccess file and type 'TEST' (or simply uncomment any line)
8. Save the file as '.htaccess' with NO file extension (should be in the same directory as your index or 'default' page)
9. Test that your server is using .htaccess by refreshing your site's homepage in the web browser
10. If your site has crashed with an Internal Server Error 500, SUCCESS -- your web server is using .htaccess!
11. Now undo whatever you just did and resave the .htaccess file.  Refresh your homepage to test again.
12. If you see you homepage is back, SUCCESS -- you're on the right track!  If not, see the Troubleshooting section.
13. From here you will want to rename every instance of 'yoursite.com' in the .htaccess file to the actual domain name you are using
14. Now read through the .htaccess BoilerPlate file and delete any sections you don't want (for example you may not want to use the www. version of your site or maybe you don't want custom error pages.)
15. Save the file and refresh your homepage to re-TEST your .htaccess directives
16. Next, edit a single line or small section of '.htaccess' to fit your wants/needs (aka adjusting cache times or the default homepage)
17. Save and TEST your .htaccess again!

18. Repeat editing and testing until you are satifisfied with your results.

19. Test multiple URLs in your web browser such as 'http://yoursite.com' AND 'http://www.yoursite.com' AND 'http://yoursite.com/index.php' AND 'http://yoursite.com/error' (where 'error' is not a real page -- see if it goes to the 404 page)
20. Watch the browser behavior and URL redirects to verify that everything is working as you intended.

{Feel free to minify your file by eliminating comment lines, but keep directives on seperate lines.}

IMPORTANT:
Caching by your web browser can be a problem.  Make sure to use the refresh/reload button often.  You may also need to CLEAR BROWSER DATA in your web browser settings, via browser plugin, or via software such as 'CCleaner' to make sure your not loading cached pages or browser cookies.

Troubleshooting:
Always include the line 'RewriteEngine on' (no quotes) and refer to your original .htaccess as well as the .htaccess BoilerPlate.
* Most often errors are caused by a coding mistake such as a missing space, extra slash character, or a # comment delimiter.
** The quickest and easiest way to fix a .htaccess problem is to RESTORE YOUR ORIGINAL BACKUP of '.htaccess' or just delete the file altogether.
*** In some cases the backslash / ESCAPE character is neccessary before puncuation ( aka http\:\/\/www\.yourwebsite\.com\/$1 ) -- Refer to the documentation and suggested website help articles and check your work meticulously. 
**** Worst case scenario you may have to call Tech Support at your web hosting provider (or check their online documentation.)

ALTERNATE METHOD:
You may want or need to custom build your .htaccess one line at a time.  Simply use our .htaccess BoilerPlate as a guide but code your own .htaccess file one line at a time, TESTING EACH LINE or two, and starting from scratch.  Include the simplest lines first but be aware that some directives may need to be in a certain order to function properly.

Recommendations:
-Leave a comment above each directive for future reference.  
-Make sure you are using the latest or prefered version of PHP available from your web host provider.
-Be meticulous about BACKING UP .htaccess and TESTING often during edits.
-Configure page caching last (and refresh pages or clear browser data often)
-Test your web domain URLs in multiple web browsers.
-If you get too Stressed Out,  T A K E  A  B R E A K  and come back to retry later.

Reference Sites:
http://www.askapache.com/htaccess/htaccess.html

https://docs.nexcess.net/category/website-management/-htaccess-file-commands/

##########  or from YOUR WEB HOST PROVIDER!  ##########



