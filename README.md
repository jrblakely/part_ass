# part_ass
Particle device assistance library

My plans here are to add a library of useful functions for inclusion into other Particle hardware projects so that they are just available when needed. Most of the functions are intended to be called from the Cloud without much (any?) application support, and to provide an easy and standard interface from within the application.

Things I've thought of so far that seem useful to me, in no particular order.
1. Report network details
1. Report memory usage and available
1. Reset device from cloud
1. Set credentials for one network and forget all others
1. Update configuration settings in EEPROM
1. Set timezone offset with DST support
1. Manage Over The Air (OTA) settings
1. Write a message from the cloud to Serial output

Also plan to make functions discrete in case memory usage is a concern. There will be an option to individually load just the functions that are needed or to request the whole shebang in one fell swoop.
