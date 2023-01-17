# getinc.training

# Situation
.edu Customers want to send SMS text message reminders to non-completers
Reminder must have links that the users can click to start training

# Complexity
Links in the reminders can be very long, e.g. to SP initiated SSO URL, long links can break across two texts for android phone, making the URLs unusable

# Solution
Shortlinks can be created using "http://getinc.training/xyz.htm" format.  This domain is registered on google, name servers are cloudflare, and the actual pages are setup in github pages, with <meta> tag and js based redirection from the shortlink to actual long link..