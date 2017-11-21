This template has a good example of using Database (DB) variables.  

The intent for this template was to apply an ACL to all the border routers WAN facing interface.  The challenge is that the WAN interface is different on each border router.  So before we had port-based config templates we needed to read the name of the border router (DB Var), then based on the name of the border router we know which interface to apply the ACL on.

There is a good explaination of this template given by me during Cisco Live, session is BRKNMS-2702 (https://www.ciscolive.com/global/on-demand-library/?search=brknms%202702#/session/1484334268555001WFgx)