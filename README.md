# chihuahua-validator

This is an abstraction of our chihuahua-1 node set up


<pre>archive1/public rpc [proposed]
vps/8gb/4 core_______________________
TBD                                  |
                                     |
               sentry1               |
 ______________vps/8gb/4 core___     |
|              Toronto, ON, CA  |    |
|                               |    |
|                               |    |
validator1                      |    |
bare metal/16gb/4 core          |    |
raid 1                     chihuahua-1
Los Angeles, CA, USA            |    |
|    |                          |    |
|    |                          |    |
|    |         sentry2          |    |
|    |_________vps/6gb/3 core___|    |
|              Ashburn, VA, USA      |
|                                    |            
|                                    |
|               sentry3              |
|_______________vps/6gb/3 core_______|
                Ashburn, VA, USA</pre>
