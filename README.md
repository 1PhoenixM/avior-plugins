This repository contains the latest .zip files to be integrated with the Avior service.

 * Firewall (Supports Floodlight. OpenDaylight support coming soon)

Firewall README.md:

Firewall Plugin to Avior.

Features:
 * Floodlight native support, Opendaylight flow equivalent support
 * Rule add/delete, view all rules, enable/disable firewall 

API:
 * /enablefirewall - Enables the Firewall (Floodlight only)
 * /disablefirewall - Disables the Firewall (Floodlight only)
 * /firewallstatus - Get the status of the firewall, enabled or disabled (Floodlight only)

 * /firewallrules/find - Get all firewall rules
 * /firewallrules/create - Post a new firewall rule
 * /firewallrules/destroy- Delete a firewall rule by name

Authors: Devin Young, Melissa Iori, Aaron Kippins
