TOSHIBA HDWR11A | 10 TB, 7200 rpm
Serial: 41R0A03HFBKG
Power-on hours: 33,499 | SMART: PASSED
Reallocated / pending / offline-uncorrectable sectors: 0 / 0 / 0
UDMA CRC errors: 0 | SMART error log: none
Lifetime temperature maximum: 59 °C; specified maximum operating temperature: 55 °C
SMART capture time: 2026-10-21 20:44 UTC

**Full captured report** (command: `smartctl -x`):

```text
smartctl 7.4 2023-08-01 r5530 [x86_64-linux-6.6.44-production+truenas] (local build)
Copyright (C) 2002-23, Bruce Allen, Christian Franke, www.smartmontools.org

=== START OF INFORMATION SECTION ===
Model Family:     Toshiba X300
Device Model:     TOSHIBA HDWR11A
Serial Number:    41R0A03HFBKG
LU WWN Device Id: 5 000039 ad8d35844
Firmware Version: 0603
User Capacity:    10,000,831,348,736 bytes [10.0 TB]
Sector Sizes:     512 bytes logical, 4096 bytes physical
Rotation Rate:    7200 rpm
Form Factor:      3.5 inches
Device is:        In smartctl database 7.3/6178
ATA Version is:   ACS-3 T13/2161-D revision 5
SATA Version is:  SATA 3.3, 6.0 Gb/s (current: 6.0 Gb/s)
Local Time is:    Wed Oct 21 16:44:20 2026 EDT
SMART support is: Available - device has SMART capability.
SMART support is: Enabled
AAM feature is:   Unavailable
APM level:        128 (minimum power consumption without standby)
Rd look-ahead:    Enabled
Write cache is:   Enabled
DSN feature is:   Unavailable
ATA Security is:  Disabled, NOT FROZEN [SEC1]
Wt Cache Reorder: Enabled

=== START OF READ SMART DATA SECTION ===
SMART overall-health self-assessment test result: PASSED

General SMART Values:
Offline data collection status:  (0x82) Offline data collection activity
                                        was completed without error.
Auto Offline Data Collection: Enabled.
Self-test execution status:      (   0) The previous self-test routine completed
                                        without error or no self-test has ever
                                        been run.
Total time to complete Offline
data collection:                (  120) seconds.
Offline data collection
capabilities:                    (0x5b) SMART execute Offline immediate.
                                        Auto Offline Data Collection on/off support.
                                        Suspend Offline collection upon new
                                        command.
                                        Offline surface scan supported.
                                        Self-test supported.
                                        No Conveyance Self-test supported.
                                        Selective self-test supported.
SMART capabilities:            (0x0003) Saves SMART data before entering
                                        power-saving mode.
                                        Supports SMART auto save timer.
Error logging capability:        (0x01) Error logging supported.
                                        General Purpose Logging supported.
Short self-test routine
recommended polling time:        (   2) minutes.
Extended self-test routine
recommended polling time:        (1009) minutes.
SCT capabilities:              (0x003d) SCT Status supported.
                                        SCT Error Recovery Control supported.
                                        SCT Feature Control supported.
                                        SCT Data Table supported.

SMART Attributes Data Structure revision number: 16
Vendor Specific SMART Attributes with Thresholds:
ID# ATTRIBUTE_NAME          FLAGS    VALUE WORST THRESH FAIL RAW_VALUE
  1 Raw_Read_Error_Rate     PO-R--   100   100   050    -    0
  2 Throughput_Performance  P-S---   100   100   050    -    0
  3 Spin_Up_Time            POS--K   100   100   001    -    7123
  4 Start_Stop_Count        -O--CK   100   100   000    -    207
  5 Reallocated_Sector_Ct   PO--CK   100   100   050    -    0
  7 Seek_Error_Rate         PO-R--   100   099   050    -    0
  8 Seek_Time_Performance   P-S---   100   100   050    -    0
  9 Power_On_Hours          -O--CK   017   017   000    -    33499
 10 Spin_Retry_Count        PO--CK   100   100   030    -    0
 12 Power_Cycle_Count       -O--CK   100   100   000    -    80
191 G-Sense_Error_Rate      -O--CK   100   100   000    -    0
192 Power-Off_Retract_Count -O--CK   100   100   000    -    54
193 Load_Cycle_Count        -O--CK   100   100   000    -    4627
194 Temperature_Celsius     -O---K   100   100   000    -    35 (Min/Max 16/59)
196 Reallocated_Event_Count -O--CK   100   100   000    -    0
197 Current_Pending_Sector  -O--CK   100   100   000    -    0
198 Offline_Uncorrectable   ----CK   100   100   000    -    0
199 UDMA_CRC_Error_Count    -O--CK   200   200   000    -    0
220 Disk_Shift              -O----   100   100   000    -    201588750
222 Loaded_Hours            -O--CK   021   017   000    -    31634
223 Load_Retry_Count        -O--CK   100   100   000    -    0
224 Load_Friction           -O---K   100   100   000    -    0
226 Load-in_Time            -OS--K   100   100   000    -    531
240 Head_Flying_Hours       P-----   100   100   001    -    0
                            ||||||_ K auto-keep
                            |||||__ C event count
                            ||||___ R error rate
                            |||____ S speed/performance
                            ||_____ O updated online
                            |______ P prefailure warning

General Purpose Log Directory Version 1
SMART           Log Directory Version 1 [multi-sector log support]
Address    Access  R/W   Size  Description
0x00       GPL,SL  R/O      1  Log Directory
0x01       SL  R/O      1  Summary SMART error log
0x02       SL  R/O     51  Comprehensive SMART error log
0x03       GPL     R/O      5  Ext. Comprehensive SMART error log
0x04       GPL,SL  R/O      8  Device Statistics log
0x06       SL  R/O      1  SMART self-test log
0x07       GPL     R/O      1  Extended self-test log
0x08       GPL     R/O      2  Power Conditions log
0x09       SL  R/W      1  Selective self-test log
0x0c       GPL     R/O    513  Pending Defects log
0x10       GPL     R/O      1  NCQ Command Error log
0x11       GPL     R/O      1  SATA Phy Event Counters log
0x24       GPL     R/O  49152  Current Device Internal Status Data log
0x25       GPL     R/O  49152  Saved Device Internal Status Data log
0x30       GPL,SL  R/O      9  IDENTIFY DEVICE data log
0x80-0x9f  GPL,SL  R/W     16  Host vendor specific log
0xe0       GPL,SL  R/W      1  SCT Command/Status
0xe1       GPL,SL  R/W      1  SCT Data Transfer

SMART Extended Comprehensive Error Log Version: 1 (5 sectors)
No Errors Logged

SMART Extended Self-test Log Version: 1 (1 sectors)
No self-tests have been logged.  [To run self-tests, use: smartctl -t]

SMART Selective self-test log data structure revision number 1
 SPAN  MIN_LBA  MAX_LBA  CURRENT_TEST_STATUS
    1        0        0  Not_testing
    2        0        0  Not_testing
    3        0        0  Not_testing
    4        0        0  Not_testing
    5        0        0  Not_testing
Selective self-test flags (0x0):
  After scanning selected spans, do NOT read-scan remainder of disk.
If Selective self-test is pending on power-up, resume after 0 minute delay.

SCT Status Version:                  3
SCT Version (vendor specific):       1 (0x0001)
Device State:                        Active (0)
Current Temperature:                    35 Celsius
Power Cycle Min/Max Temperature:     24/35 Celsius
Lifetime    Min/Max Temperature:     16/59 Celsius
Specified Max Operating Temperature:    55 Celsius
Under/Over Temperature Limit Count:   0/0

SCT Temperature History Version:     2
Temperature Sampling Period:         1 minute
Temperature Logging Interval:        1 minute
Min/Max recommended Temperature:      5/55 Celsius
Min/Max Temperature Limit:           -40/70 Celsius
Temperature History Size (Index):    478 (401)

Index    Estimated Time   Temperature Celsius
 402    2026-10-21 08:47    51  ********************************
 ...    ..(  3 skipped).    ..  ********************************
 406    2026-10-21 08:51    51  ********************************
 407    2026-10-21 08:52    52  *********************************
 408    2026-10-21 08:53    51  ********************************
 ...    ..(  2 skipped).    ..  ********************************
 411    2026-10-21 08:56    51  ********************************
 412    2026-10-21 08:57    52  *********************************
 413    2026-10-21 08:58    51  ********************************
 ...    ..(  4 skipped).    ..  ********************************
 418    2026-10-21 09:03    51  ********************************
 419    2026-10-21 09:04    52  *********************************
 420    2026-10-21 09:05    51  ********************************
 ...    ..(  2 skipped).    ..  ********************************
 423    2026-10-21 09:08    51  ********************************
 424    2026-10-21 09:09    52  *********************************
 425    2026-10-21 09:10    51  ********************************
 ...    ..(  7 skipped).    ..  ********************************
 433    2026-10-21 09:18    51  ********************************
 434    2026-10-21 09:19    52  *********************************
 435    2026-10-21 09:20    51  ********************************
 436    2026-10-21 09:21    51  ********************************
 437    2026-10-21 09:22    52  *********************************
 438    2026-10-21 09:23    51  ********************************
 439    2026-10-21 09:24    51  ********************************
 440    2026-10-21 09:25    51  ********************************
 441    2026-10-21 09:26    52  *********************************
 442    2026-10-21 09:27    52  *********************************
 443    2026-10-21 09:28    51  ********************************
 ...    ..(286 skipped).    ..  ********************************
 252    2026-10-21 14:15    51  ********************************
 253    2026-10-21 14:16    52  *********************************
 ...    ..( 17 skipped).    ..  *********************************
 271    2026-10-21 14:34    52  *********************************
 272    2026-10-21 14:35    51  ********************************
 273    2026-10-21 14:36    52  *********************************
 274    2026-10-21 14:37    51  ********************************
 275    2026-10-21 14:38    52  *********************************
 276    2026-10-21 14:39    52  *********************************
 277    2026-10-21 14:40    51  ********************************
 278    2026-10-21 14:41    51  ********************************
 279    2026-10-21 14:42    52  *********************************
 280    2026-10-21 14:43    51  ********************************
 281    2026-10-21 14:44    52  *********************************
 282    2026-10-21 14:45    51  ********************************
 ...    ..(  3 skipped).    ..  ********************************
 286    2026-10-21 14:49    51  ********************************
 287    2026-10-21 14:50    52  *********************************
 ...    ..(  3 skipped).    ..  *********************************
 291    2026-10-21 14:54    52  *********************************
 292    2026-10-21 14:55    51  ********************************
 ...    ..(  3 skipped).    ..  ********************************
 296    2026-10-21 14:59    51  ********************************
 297    2026-10-21 15:00    52  *********************************
 298    2026-10-21 15:01    52  *********************************
 299    2026-10-21 15:02    51  ********************************
 300    2026-10-21 15:03    52  *********************************
 301    2026-10-21 15:04    51  ********************************
 302    2026-10-21 15:05    52  *********************************
 303    2026-10-21 15:06    51  ********************************
 304    2026-10-21 15:07    51  ********************************
 305    2026-10-21 15:08    52  *********************************
 306    2026-10-21 15:09    51  ********************************
 307    2026-10-21 15:10    52  *********************************
 308    2026-10-21 15:11    52  *********************************
 309    2026-10-21 15:12    51  ********************************
 310    2026-10-21 15:13    52  *********************************
 311    2026-10-21 15:14    52  *********************************
 312    2026-10-21 15:15    51  ********************************
 313    2026-10-21 15:16    52  *********************************
 314    2026-10-21 15:17    51  ********************************
 315    2026-10-21 15:18    52  *********************************
 316    2026-10-21 15:19    51  ********************************
 317    2026-10-21 15:20    52  *********************************
 318    2026-10-21 15:21    51  ********************************
 319    2026-10-21 15:22    52  *********************************
 ...    ..(  5 skipped).    ..  *********************************
 325    2026-10-21 15:28    52  *********************************
 326    2026-10-21 15:29    53  **********************************
 327    2026-10-21 15:30    52  *********************************
 328    2026-10-21 15:31    53  **********************************
 ...    ..( 16 skipped).    ..  **********************************
 345    2026-10-21 15:48    53  **********************************
 346    2026-10-21 15:49    54  ***********************************
 347    2026-10-21 15:50    54  ***********************************
 348    2026-10-21 15:51    54  ***********************************
 349    2026-10-21 15:52    53  **********************************
 350    2026-10-21 15:53    54  ***********************************
 ...    ..(  8 skipped).    ..  ***********************************
 359    2026-10-21 16:02    54  ***********************************
 360    2026-10-21 16:03    53  **********************************
 ...    ..( 10 skipped).    ..  **********************************
 371    2026-10-21 16:14    53  **********************************
 372    2026-10-21 16:15     ?  -
 373    2026-10-21 16:16    22  ***
 ...    ..(  3 skipped).    ..  ***
 377    2026-10-21 16:20    22  ***
 378    2026-10-21 16:21     ?  -
 379    2026-10-21 16:22    24  *****
 380    2026-10-21 16:23    24  *****
 381    2026-10-21 16:24    24  *****
 382    2026-10-21 16:25    25  ******
 383    2026-10-21 16:26    25  ******
 384    2026-10-21 16:27    26  *******
 385    2026-10-21 16:28    26  *******
 386    2026-10-21 16:29    27  ********
 387    2026-10-21 16:30    28  *********
 388    2026-10-21 16:31    28  *********
 389    2026-10-21 16:32    29  **********
 390    2026-10-21 16:33    29  **********
 391    2026-10-21 16:34    30  ***********
 392    2026-10-21 16:35    31  ************
 393    2026-10-21 16:36    31  ************
 394    2026-10-21 16:37    32  *************
 395    2026-10-21 16:38    32  *************
 396    2026-10-21 16:39    33  **************
 397    2026-10-21 16:40    33  **************
 398    2026-10-21 16:41    34  ***************
 399    2026-10-21 16:42    34  ***************
 400    2026-10-21 16:43    34  ***************
 401    2026-10-21 16:44    35  ****************

SCT Error Recovery Control:
           Read:     70 (7.0 seconds)
          Write:     70 (7.0 seconds)

Device Statistics (GP Log 0x04)
Page  Offset Size        Value Flags Description
0x01  =====  =               =  ===  == General Statistics (rev 3) ==
0x01  0x008  4              80  ---  Lifetime Power-On Resets
0x01  0x010  4           33499  ---  Power-on Hours
0x01  0x018  6     64945653417  ---  Logical Sectors Written
0x01  0x020  6       289959215  ---  Number of Write Commands
0x01  0x028  6    191195346420  ---  Logical Sectors Read
0x01  0x030  6      1201839908  ---  Number of Read Commands
0x01  0x038  6    120596400000  ---  Date and Time TimeStamp
0x02  =====  =               =  ===  == Free-Fall Statistics (rev 1) ==
0x02  0x010  4               0  ---  Overlimit Shock Events
0x03  =====  =               =  ===  == Rotating Media Statistics (rev 1) ==
0x03  0x008  4              30  ---  Spindle Motor Power-on Hours
0x03  0x010  4             615  ---  Head Flying Hours
0x03  0x018  4            4627  ---  Head Load Events
0x03  0x020  4               0  ---  Number of Reallocated Logical Sectors
0x03  0x028  4               6  ---  Read Recovery Attempts
0x03  0x030  4               0  ---  Number of Mechanical Start Failures
0x03  0x038  4               0  ---  Number of Realloc. Candidate Logical Sectors
0x03  0x040  4              54  ---  Number of High Priority Unload Events
0x04  =====  =               =  ===  == General Errors Statistics (rev 1) ==
0x04  0x008  4               0  ---  Number of Reported Uncorrectable Errors
0x04  0x010  4               0  ---  Resets Between Cmd Acceptance and Completion
0x05  =====  =               =  ===  == Temperature Statistics (rev 1) ==
0x05  0x008  1              35  ---  Current Temperature
0x05  0x010  1              51  N--  Average Short Term Temperature
0x05  0x018  1              49  N--  Average Long Term Temperature
0x05  0x020  1              59  ---  Highest Temperature
0x05  0x028  1              16  ---  Lowest Temperature
0x05  0x030  1              57  N--  Highest Average Short Term Temperature
0x05  0x038  1              29  N--  Lowest Average Short Term Temperature
0x05  0x040  1              50  N--  Highest Average Long Term Temperature
0x05  0x048  1              35  N--  Lowest Average Long Term Temperature
0x05  0x050  4            6173  ---  Time in Over-Temperature
0x05  0x058  1              55  ---  Specified Maximum Operating Temperature
0x05  0x060  4               0  ---  Time in Under-Temperature
0x05  0x068  1               5  ---  Specified Minimum Operating Temperature
0x06  =====  =               =  ===  == Transport Statistics (rev 1) ==
0x06  0x008  4            1211  ---  Number of Hardware Resets
0x06  0x010  4             210  ---  Number of ASR Events
0x06  0x018  4               0  ---  Number of Interface CRC Errors
0x07  =====  =               =  ===  == Solid State Device Statistics (rev 1) ==
                                |||_ C monitored condition met
                                ||__ D supports DSN
                                |___ N normalized value

Pending Defects log (GP Log 0x0c)
No Defects Logged

SATA Phy Event Counters (GP Log 0x11)
ID      Size     Value  Description
0x0001  4            0  Command failed due to ICRC error
0x0002  4            0  R_ERR response for data FIS
0x0003  4            0  R_ERR response for device-to-host data FIS
0x0004  4            0  R_ERR response for host-to-device data FIS
0x0005  4            0  R_ERR response for non-data FIS
0x0006  4            0  R_ERR response for device-to-host non-data FIS
0x0007  4            0  R_ERR response for host-to-device non-data FIS
0x0008  4            0  Device-to-host non-data FIS retries
0x0009  4            3  Transition from drive PhyRdy to drive PhyNRdy
0x000a  4            1  Device-to-host register FISes sent due to a COMRESET
0x000b  4            0  CRC errors within host-to-device FIS
0x000d  4            0  Non-CRC errors within host-to-device FIS
```
