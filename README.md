# free-tier-abuse-public
Some screenshots of a pretty spiffy architecture project that takes advantage of the generosity of Jeff Bezos

![Cost Savings](./screenshots/costSavings.png)

Pretty cheap, right?

![Stacks](./screenshots/stacksOnStacks.png)

10 stacks but very easy to deploy.  All done through ci/cd or a Makefile target

![Actions](./screenshots/githubActions.png)

Github actions, also cheap.  1,000 minutes free per month
![Fast](./screenshots/fastCiCd.png)

Esp when ur fast...

![Makefile](./screenshots/makefile.png)

Local development starts in top level, nice makefile for easy autocomplete.  Type ```make up``` to get started after logging in to AWS via sso

![docker up](./screenshots/dockerUp.png)

All dockerized for easy local development.  Traefik does the routing via docker-compose params

![Makefile](./screenshots/traefik.png)

Shots from a compose file

![SSL LocalDev](./screenshots/sslLocalDevDomain.png)

SSL for local development.  Does some magic with some local DNS and some local ca generation scripts/traefik
Makes working on service workers easy


![Workspaces](./screenshots/workspaces.png)

Using some node workspace stuff to make dep management tolerable


![Workspaces](./screenshots/topLevel.png)

Pretty neat top level.  Rarely have to leave it.  Workspaces + good makefile discipline

![Dev Resources](./screenshots/devResources.png)

![Frontend](./screenshots/veryBeefyFrontend.png)

A Very beefy angular frontend with all the bells and whistles.  Like, all of them.  ALL of the bells and whistles.  All of them.

![API With Layers Loaded Locally](./screenshots/layersEqualsFast.png)

Hot reloading, Typescript and layers make for a fast dev experience.  Lots of custom dockerized SAM nonsense.

![lighthouse!](screenshots/lighthouse.png)
*Note -- its only 99% there because im too lazy to turn off my browser plugins, and they make it not 100.  It actually is 100%.


Just a bunch of over-engineered slop!  But it doesnt cost a fortune!
