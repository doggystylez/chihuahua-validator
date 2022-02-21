# chihuahua-validator

This is an abstraction of our chihuahua-1 node set up
<pre>

                 validator
     ______bare metal/64gb/12cpu______
     |               |                |
     |               |                |
  sentry1         sentry2          sentry3
vps/8gb/4cpu    vps/8gb/4cpu     vps/8gb/4cpu
     |               |                |
     |               |                |
     |__________chihuahua-1___________|</pre>
