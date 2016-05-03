#Disavow automator#

##How it works##

1. Put your current disavow file in `disavow.txt`

2. Put the URLs you want to check in `urls.txt`

3. Download any Python dependencies

4. Open the project in your terminal and run `python checker.py`

##What it does##

The script will open any URLs that aren't in either your URLs file or your whitelist in the browser

You can spot check them (most spammy sites you can spot instantly), and say if they're spam (y or n). If you say "y" the URL will be added to `disavow.txt`. If you say "n" the URL will be added to the whitelist.

Note: This doesn't yet work for domain:url.com syntax.