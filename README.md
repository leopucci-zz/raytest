# raytest
setting up a cloudfront script to orchestrate the creation of chef server, postgres elastic db, rails servers, and tie up everything together. 

Tasks:

1 - Set 1 server with CHEF Server - installation ok, the cfn-init must be using some firewall/proxy that fails on the instalation test. But instalation is ok. 

2 - Set the other 2 servers with Rails + Nginx - Need to deploy chef client first. Chefdk being deployed. Need to add the clients to the server

3 - Deploy all conf of the load balancer only for the two Rails Instances. Done

4 - Create Recipe for the Postgres sql conection configuration for Rails +Nginx Later

5 - Think in a way of deploying the Ruby APP on-the-fly for the 2 instances. (GitHub maybe? Chef recipes will teach me how). Food for thought! 

Later tasks:

Create ruby app package
-- Use Js "data-" for unobstrusive JS, just like cakePhp conventions
-- Create controller DB <-> SpreadSheetCells
Theme up the MVC

Deploy first crap html.erb

Convert crap to pretty ruby post background with XHR ajax requests. 

Think/LMGTFY on MQTT or Websocket with ruby. 
https://github.com/faye/faye-websocket-ruby
Maybe use memcached for this, as websockets can be firewalled. 
Develop interface or generate with Jtables or other jscript related stuff

Reconfigure the Chef recipe to deploy ruby new app details. 

Let´s Roll!
