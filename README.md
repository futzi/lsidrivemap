lsidrivemap
===========

I have a 24-disk drive enclosure. This tool is to determine
which disk (sda/sdb/etc) is in which drive slot. It also 
shows the drive temperature of each slot.

Example output:

    root@nano:/usr/src# ./lsidrivemap temp

    | 28 | 32 | 35 | ?  |
    | 30 | 31 | 37 | 36 |
    | 29 | ?  | 38 | 37 |
    | 29 | 31 | 37 | 35 |
    | 28 | 36 | 36 |    |
    |    |    | 33 |    |

    root@nano:/usr/src# ./lsidrivemap disk

    | sdn | sdo | sdp |     |
    | sdq | sdr | sdt | sds |
    | sde |     | sdl | sdi |
    | sdf | sdg | sdj | sdk |
    | sda | sdb | sdc |     |
    |     |     | sdd |     |


