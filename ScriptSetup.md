# **Run script from your personal server** #
  1. Checkout the code from [How to: Add MyEpisodes.com to Google Calendar](http://goo.gl/2vfs8).
  1. Enter your MyEpisodes.com username, and md5-password`**` in `myepisodes2ical.php` for the variables uid and md5.
  1. Modify the timezone in `myepisodes2ical.php` to your local timezone.
  1. Upload to your personal web server

`**` Your MD5 password is NOT your normal password. To find your MD5 password, return to MyEpisodes.com. Log in and go to the [MyEpisodes.com Control Panel](http://www.myepisodes.com/cp.php). Copy your MD5 hashed password and paste it into `myepisodes2ical.php`.


---


# **Google Calendar Setup** #

_Disclaimer: I've only used/tested with Google Calendar, results may vary with other calendar clients_
  1. Log into your Google Calendar
  1. Click the arrow to the right of 'Other calendars' and select 'Add by URL'
  1. Enter `http://[`_your web server_`]/myepisodes2ical.php` as the URL and click 'Add calendar'
  1. It may take up to 24 hours for you to start seeing your TV Episode feed populate your calendar, this is due to how often Google Calendar refreshes iCal feeds. (something nobody can control...)