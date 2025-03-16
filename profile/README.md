## Hi there 👋

Welcome to PhoneBo.cx! This is where [xrobau](https://github.com/xrobau) [(Sponsor him!)](https://github.com/sponsors/xrobau) is creating his new Open Source PBX, amongst other things!

He's learned a few things from FreePBX, so it's going to be a bit different. Here's what the plans are currently:

* Multi-tenant from the start. The original design of FreePBX made it almost impossible to be multi-tenant without massive complexity.
* A simple graph-based UX. You will be able to link Trunks to Inbound Routes to Time Conditions to IVRs to Ring Groups, just by drawing a line. You will still have a text-based mode for complicated configurations, but 95% of people never used more than just the basics. [Here's a preview](http://imgur.com/a/HaSXe3r).
* Freeswitch/Kamailio front-ends. This means it has a SBC and firewall built in!
* That *also* means this is horizontally scalable! You can run this on a PI and handle 20 calls, or a cluster of machines and handle 20,000 calls.
* Secure by default, as everything is built around an immutable operating system. If the machine gets hacked, nothing can be changed, as it's all read-only
* AI built right in. You can plug into any compatible AI services (Speech to Text, Dictation, Assistants) simply by adding their graph to the UI.
* AGPL3 Licenced, from the start - but with the option for companies to purchase other licences (which is how we are hoping to monetize this!)


See the 'Discussions' repo as things get started!
