# Unbound Config
This is my configuration for Unbound. Tries to be as well documented as I can, sourcing descriptions from the [man page](https://nlnetlabs.nl/documentation/unbound/unbound.conf/)  Organized into directories. [Exemplar unbound.conf](https://github.com/NLnetLabs/unbound/blob/master/doc/example.conf.in) can be found in the official [NLnetLabs/Unbound](https://github.com/NLnetLabs/unbound/) repo. You can source environment variables in the config like this `"@ENV_VARIABLE_NAME@".

## Directories
- conf-enabled  
Server configuration entries that are enabled
- conf-available  
Server configuration entries that are disabled 
- zones-enabled   
Auth/Forward/Stub zone configurations that are enabled
- zones-available   
Auth/Forward/Stub zone configurations that are disabled
- local-enabled   
Local zone definitions/entries that are enabled
- local-available  
Local zone definitions/entries that are disabled
- extensions-enabled  
Extras like unbound-control that are enabled
- extensions-available  
Extras like unbound-control that are disabled

