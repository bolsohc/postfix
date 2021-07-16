# Postfix role 

* Please run 'custom-facts' before using this role!
  * Role expects presence of ```ansible_local.datacenter.location``` fact
  * Region is determined using this fact via ```dc_to_region``` map in ```defaults/main.yml```
* Regions supported: ```US```, ```CA```, ```AP``` 
  * Postfix values for each region are specified in ```defaults/main.yml```
