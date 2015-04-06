==== Zen Cart - Customer Loyalty Discount Order Total Module ====

=== Tested on Zen Cart 1.3.X, 1.5.0, 1.5.1 & PHP 5.3.21 & PHP 5.4.30===

= This module is an beginner installation. =

###########################################################################################
#                                                                                         #
#                                                                                         #
# Please REPORT bugs to support@pro-webs.net                                              #
# Support via our helpdesk here https://pro-webs-support.com/                             #
#                                                                                         #
#                                                                                         #
###########################################################################################

Zen Cart Customer Loyalty Discount

This addon is an beginner installation for Zen Cart 1.3.x & 1.5.x and was 
tested on PHP 5.4.30

The purpose of this Zen Cart order total module is to provide a basic Customer 
Loyalty Program/Discount Scheme, that rewards customers with discounts against 
each order based upon the amount they have spent in prior periods.

This module, at the time of a customer order being placed, totals up the value 
of all previous orders this customer has placed over a pre-defined (in admin) 
rolling period of time and then applies a discount rate to this order according 
to a table of discount rates also pre-defined (in admin) that correspond to the 
amount spent over the rolling period.

For example, in admin you have set the pre-defined rolling period to a month, 
and set up a table of discounts that gives 5.0% discount if they have spent 
over $1000 in the previous month (i.e previous 31 days, not calendar month), 
or 7.5% if they have spent over $1500 in the previous month.


===Database Changes===
Configuration database changes as in all order total modules.


===Core File Edits===
NONE


+++++++++++===Basic Installation===+++++++++++


1. !!!! Backup your database and affected files !!!!

 
================================================================  
   
   
2. Upload the package files & directories taking care to maintain the folder
   structure. For fresh installs, there are no overwrites.

================================================================


3. Go to Modules >> Order Total >> Loyalty and set it up



================================================================


That's it!        


++++++++++===EOF Basic Installation===++++++++++			
       
       
===Change History===

Date       Version  Who             Why
===============================================================================
06/10/2003  1.0	  Simon Pritchard	| Initial Release  
04/03/2004  1.1   Clement Nicolaescu (www.osCoders.biz) | New option added
06/30/2004  1.2   rainer langheiter (http://rainer.langheiter.com // www.FiloSoFisch.com) |  ported from OSC to ZEN
06/30/2013  1.3   PRO-Webs.net | Revived for PHP 5.X and Zen Cart 1.5.X		
				