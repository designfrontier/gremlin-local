# gremlin-local

a simple docker-compose to get you up and running with tinkerpop and grephexp as
a UI for it. The one downside to this base setup is that your data is ephemeral.
So you get a fresh DB everytime you restart it (nice for testing... and some 
development). This should be pretty easy to fix with some tweaks to the
`docker-compose.yml` file, adding a volume etc.

## dory compatible

If you are running dory the services will be at `gremlin-ui.docker:8183` and 
`gremlin.docker:8182`.

## credit

A good chunk of this came from (https://github.com/joov/gremlin-demo)[https://github.com/joov/gremlin-demo]
check it out.