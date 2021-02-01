# sonicWallBruteForce
Script to brute force logins to SonicWall

Based on gist by vasuman to do autologins
https://gist.github.com/vasuman/fa750a6fe57fc8a73aff


I don't have a sonic wall, or valid creds, so not fully tested. Please let me know if this isn't working as expected.

If it turns out this really does work, I'll focus on performance later. 

Wet paint for sure. 

@hoodoer



Options:
-host          host to target, e.g 'https://somesonicwall.xyz' (REQUIRED)
-userlist      user list (REQUIRED)
-password      password to use (single).
-passwordlist  password list. Seriously consider setting a delay value.
-proxy         HTTP proxy.
-delay         how many seconds to wait before moving to next password in list.
-debug         print extra stuffs.
