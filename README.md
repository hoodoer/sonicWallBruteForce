# sonicWallBruteForce
Script to brute force logins to SonicWall

Based on gist by vasuman to do autologins
https://gist.github.com/vasuman/fa750a6fe57fc8a73aff


I don't have a sonic wall, or valid creds, so not fully tested. Please let me know if this isn't working as expected.

If it turns out this really does work, I'll focus on performance later. 

Wet paint for sure. 

@hoodoer



Options:
    parser.add_argument("-host", help="host to target, e.g 'https://somesonicwall.xyz' (REQUIRED).", required=True)
    parser.add_argument("-userlist", help="user list (REQUIRED).", required=True)
    parser.add_argument("-password", help="password to use (single).")
    parser.add_argument("-passwordlist", help="password list. Seriously consider setting a delay value.")
    parser.add_argument("-proxy", help="HTTP proxy.")
    parser.add_argument("-delay", help="how many seconds to wait before moving to next password in list.")
    parser.add_argument("-debug", help="print extra stuffs.", action='store_true')
