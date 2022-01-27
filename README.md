# chihuahua-validator

This is an abstraction of our chihuahua-1 node set up


<pre>archive1/public rpc [proposed]
vps/8gb/4cpu________________________________
TBD                                         |
                                            |
                                            |
                sentry1                     |
 _______________vps/8gb/4cpu__________      |
|               Toronto, ON, CA       |     |
|                                     |     |
|                                     |     |
validator1                            |     |
bare metal/16gb/4cpu                  |     |
raid 1                            chihuahua-1
Los Angeles, CA, USA                  |     |
|     |                               |     |
|     |                               |     |
|     |         sentry2               |     |
|     |_________vps/6gb/3cpu__________|     |
|               Ashburn, VA, USA            |
|                                           |
|                                           |
|               sentry3                     |
|_______________vps/4gb/2cpu________________|
                San Francisco, CA, USA</pre>
              
              
