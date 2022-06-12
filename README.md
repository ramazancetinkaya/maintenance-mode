# maintenance-mode
Create a website maintenance message with an .htaccess file

## How do I do this?

1) Creating an **.htaccess** file on your web server
2) If your site is going into maintenance, you can forward visitors to a maintenance message automatically. First, you must create a file named **maintenance.html** in your web directory.
3) You can rename the **'maintenance.html'** file to *whatever you want*.
4) Then, add the following to your **.htaccess** file.

### Notes

If you now visit the site, it automatically loads the contents of the **maintenance.html** file, but the URL does not change.

You can replace **[L]** with **[R=307,L]** if you prefer that the user see the URL change to **example.com/maintenance.html**. However, this is usually not what you want.
