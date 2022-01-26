# chihuahua-validator

This is an abstraction of our chihuahua-1 node set up


<pre>archive1/public rpc [proposed]
vps/8gb/4 core_____________________________
TBD                                        |
                                           |
                    sentry1                |
 ___________________vps/8gb/4 core____     |
|                   Toronto, ON, CA   |    |
|                                     |    |
|                                     |    |
validator1                            |    |
bare metal/16gb/4 core           chihuahua-1
raid 1                                |    |
Los Angeles, CA, USA                  |    |
|    |                                |    |
|    |                                |    |
|    |              sentry2           |    |
|    |______________vps/6gb/3core_____|    |
|                   Ashburn, VA, USA       |
|                                          |            
|                                          |
|                   sentry3                |
|___________________vps/6gb/3 core_________|
                    Ashburn, VA, USA</pre>
