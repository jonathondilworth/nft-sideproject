# SIDEPROJECT: NFT Marketplace (Boutique Style)

*Current Stage: Planning*

URL (NOT CURRENTLY IN USE): https://ownly.art/

Considerations:

* Add CNAME DNS record: https://the.ownly.art/ - a play on the concept of an NFT
* This is a marketplace for everyone.
* Emphasis on physical art if possible.
* NOTE: SIDE PROJECT.

Literally throwing this together v. hacky.

Implementation Details:

*I don't believe this is going to go anywhere, it's more of a side project to assist learning. Thus: Scalability and other considerations for deployment of production applications won't generally be considered with any seriousness (unless it miraculously goes somewhere; at which point would probably reconsider some of the infrastructure, deployment pipeline(s), architectural decisions, you know the score).*

* Server Hosted In Netherlands
* VPS Instance: 2GB RAM, 1 vCPU, $10 / month sorta deal.
* Front-end: Bootstrap, Generic CSS.
* SHOULD probably consider Tailwind CSS and other Laravel components and 'web-kit' tools...
* Backend: Laravel 8.x, PHP-FPM 8.x, NGINX, (tried and tested - stands the age of time) mySQL (OS: Ubuntu 20.x LTS - can't remember the latest LTS version)
* Other components: going to be looking at integrating tooling such as BlockFrost, or might see what GimbaLabs are working on (Reminder: Jump Into That Discord)
* Further components: NFT Vending Machine Scripts (ATM would have to manually create NFTs, not a massive deal really. Solution: shell scripts & possibly something like Ansible Playbooks; need to be very cautious - security).
* Additional Infrastructure: consider a VPC: Cardano Node Instance, Application Instance, SPINHX Indexing Instance for full text search, single DB instance).

### Additional Considerations

* Load Balancing, Security
* YES: Side Project, but I won't likely host it forever if it generates nothing, so possibly review a basic Business Model Canvas, etc).

TODO: UPDATE READ ME.
