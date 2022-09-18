---
title: "Server Configuration Maintenance"
date: 2022-04-29T19:53:45+01:00
author: "Pluxeur Engineering Team"
authorLink: "https://pluxeur.netlify.app"
draft: false
---

**The timeline of the update can be found at the bottom of the post.**

## The reason for reconfiguration
The reconfiguration of the servers came after a recent security issue was found in our backend infrastructure. The on-call engineers scheduled the maintenance for 20:00 on the 29/04/2022. This

We also decided it was a better idea to move all of our projects to a GitHub organization rather than a single account & remove our monorepo from our workflow.

## So what did we do
- We have added a new server **NE2**, this contains all of our new websites.
- We moved all of our partnered website to **NE1**, this is to prevent overload.
- We separated our monorepo into separate repos under an organization.

## Future plans
- We hope our new strategy will help grow our servers without an impact on performance.
- We want to open our websites & services to more people.
- We are engineering our own Load Balancer to help us distribute our services.

## New server locations & addresses
Main Website - Now located [here](https://pluxeur.netlify.app/)  
Events Website - Now located [here](https://pluxeur-events.netlify.app/)  
Maps Website - Now located [here](https://pluxeur-maps.netlify.app/)  
Clock Website - Now located [here](https://pluxeur-clock.netlify.app/)  
Stopwatch Website - Now located [here](https://pluxeur-stopwatch.netlify.app/)  

## Maintenance timeline
20:00 - Maintenance started.  
20:30 - Server configuration was published to the test server.  
20:35 - Response received that the configuration was ready for rollout.  
20:40 - Server configuration was rolled out across the main servers.  
20:53 - Updated was posted to the status page informing of the config changes.  
21:09 - Server config was received & fully updated across all of our servers.  
21:10 - Monorepo was taken apart & separated into different folders ready for committing.  
**21:20 - Pluxeur's main website was published as a separate repo, for the first time in a year.**  
21:22 - Pluxeur Events, Maps, Stopwatch & Clock were published as seperate repos.  
21:28 - Pluxeur's main website was published fully & available under a new domain.  
21:29 - Pluxeur Events, Maps, Stopwatch & Clock were published fully & available under a new domain.  
21:30 - Status page updated to show maintenance has been completed.  

**[You can read the status page updates here](https://pluxeur.instatus.com/cl2ksac2x1423128rvn5mq0pr1o6)**