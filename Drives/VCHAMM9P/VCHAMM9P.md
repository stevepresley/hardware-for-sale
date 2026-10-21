WDC WD101EFAX-68LDBN0 | 10 TB, 5400 rpm
Serial: VCHAMM9P
Power-on hours: 46,428 | SMART: PASSED
Reallocated / pending / offline-uncorrectable sectors: 0 / 0 / 0
UDMA CRC errors: 19; error log records interface ICRC/ABRT errors
SMART capture time: 2026-10-21 20:44 UTC

**Full captured report** (command: `smartctl -x`):

```text
smartctl 7.4 2023-08-01 r5530 [x86_64-linux-6.6.44-production+truenas] (local build)
Copyright (C) 2002-23, Bruce Allen, Christian Franke, www.smartmontools.org

=== START OF INFORMATION SECTION ===
Model Family:     Western Digital Red Plus
Device Model:     WDC WD101EFAX-68LDBN0
Serial Number:    VCHAMM9P
LU WWN Device Id: 5 000cca 0b0d2ece0
Firmware Version: 81.00A81
User Capacity:    10,000,831,348,736 bytes [10.0 TB]
Sector Sizes:     512 bytes logical, 4096 bytes physical
Rotation Rate:    5400 rpm
Form Factor:      3.5 inches
Device is:        In smartctl database 7.3/6178
ATA Version is:   ACS-2, ATA8-ACS T13/1699-D revision 4
SATA Version is:  SATA 3.2, 6.0 Gb/s (current: 6.0 Gb/s)
Local Time is:    Wed Oct 21 16:44:20 2026 EDT
SMART support is: Available - device has SMART capability.
SMART support is: Enabled
AAM feature is:   Unavailable
APM level:        164 (intermediate level without standby)
Rd look-ahead is: Enabled
Write cache is:   Enabled
DSN feature is:   Unavailable
ATA Security is:  Disabled, NOT FROZEN [SEC1]
Wt Cache Reorder: Enabled

=== START OF READ SMART DATA SECTION ===
SMART overall-health self-assessment test result: PASSED

General SMART Values:
Offline data collection status:  (0x80) Offline data collection activity
                                        was never started.
Auto Offline Data Collection: Enabled.
Self-test execution status:      (   0) The previous self-test routine completed
                                        without error or no self-test has ever
                                        been run.
Total time to complete Offline
data collection:                (   93) seconds.
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
recommended polling time:        (1123) minutes.
SCT capabilities:              (0x003d) SCT Status supported.
                                        SCT Error Recovery Control supported.
                                        SCT Feature Control supported.
                                        SCT Data Table supported.

SMART Attributes Data Structure revision number: 16
Vendor Specific SMART Attributes with Thresholds:
ID# ATTRIBUTE_NAME          FLAGS    VALUE WORST THRESH FAIL RAW_VALUE
  1 Raw_Read_Error_Rate     PO-R--   100   100   016    -    0
  2 Throughput_Performance  --S---   130   130   054    -    108
  3 Spin_Up_Time            POS---   188   188   024    -    251 (Average 612)
  4 Start_Stop_Count        -O--C-   100   100   000    -    287
  5 Reallocated_Sector_Ct   PO--CK   100   100   005    -    0
  7 Seek_Error_Rate         -O-R--   100   100   067    -    0
  8 Seek_Time_Performance   --S---   128   128   020    -    18
  9 Power_On_Hours          -O--C-   094   094   000    -    46428
 10 Spin_Retry_Count        -O--C-   100   100   060    -    0
 12 Power_Cycle_Count       -O--CK   100   100   000    -    287
192 Power-Off_Retract_Count -O--CK   099   099   000    -    1868
193 Load_Cycle_Count        -O--C-   099   099   000    -    1868
194 Temperature_Celsius     -O----   196   196   000    -    33 (Min/Max 10/57)
196 Reallocated_Event_Count -O--CK   100   100   000    -    0
197 Current_Pending_Sector  -O---K   100   100   000    -    0
198 Offline_Uncorrectable   ---R--   100   100   000    -    0
199 UDMA_CRC_Error_Count    -O-R--   200   200   000    -    19
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
0x02       SL  R/O      1  Comprehensive SMART error log
0x03       GPL     R/O      1  Ext. Comprehensive SMART error log
0x04       GPL,SL  R/O    256  Device Statistics log
0x04       SL      R/O    255  Device Statistics log
0x06       SL  R/O      1  SMART self-test log
0x07       GPL     R/O      1  Extended self-test log
0x08       GPL     R/O      2  Power Conditions log
0x09       SL  R/W      1  Selective self-test log
0x0c       GPL     R/O   5501  Pending Defects log
0x10       GPL     R/O      1  NCQ Command Error log
0x11       GPL     R/O      1  SATA Phy Event Counters log
0x12       GPL     R/O      1  SATA NCQ Non-Data log
0x13       GPL     R/O      1  SATA NCQ Send and Receive log
0x15       GPL     R/W      1  Rebuild Assist log
0x21       GPL     R/O      1  Write stream error log
0x22       GPL     R/O      1  Read stream error log
0x24       GPL     R/O    256  Current Device Internal Status Data log
0x25       GPL     R/O    256  Saved Device Internal Status Data log
0x30       GPL,SL  R/O      9  IDENTIFY DEVICE data log
0x80-0x9f  GPL,SL  R/W     16  Host vendor specific log
0xe0       GPL,SL  R/W      1  SCT Command/Status
0xe1       GPL,SL  R/W      1  SCT Data Transfer

SMART Extended Comprehensive Error Log Version: 1 (1 sectors)
Device Error Count: 19 (device log contains only the most recent 4 errors)
        CR     = Command Register
        FEATR  = Features Register
        COUNT  = Count (was: Sector Count) Register
        LBA_48 = Upper bytes of LBA High/Mid/Low Registers ]  ATA-8
        LH     = LBA High (was: Cylinder High) Register    ]   LBA
        LM     = LBA Mid (was: Cylinder Low) Register      ] Register
        LL     = LBA Low (was: Sector Number) Register     ]
        DV     = Device (was: Device/Head) Register
        DC     = Device Control Register
        ER     = Error register
        ST     = Status register
Powered_Up_Time is measured from power on, and printed as
DDd+hh:mm:SS.sss where DD=days, hh=hours, mm=minutes,
SS=sec, and sss=millisec. It "wraps" after 49.710 days.

Error 19 [2] occurred at disk power-on lifetime: 43011 hours (1792 days + 3 hours)
  When the command that caused the error occurred, the device was active or idle.

  After command completion occurred, registers were:
  ER -- ST COUNT  LBA_48  LH LM LL DV DC
  -- -- -- == -- == == == == == == == ==
  84 -- 43 00 00 00 00 00 00 00 00 00 00 00  Error: ICRC, ABRT at LBA = 0x00000000 = 0

  Commands leading to the command that caused the error were:
  CR FEATR COUNT  LBA_48  LH LM LL DV DC  Powered_Up_Time  Command/Feature_Name
  -- == -- -- == == == == -- -- -- -- --  ---------------  --------------------
  60 00 28 00 60 00 01 28 44 d5 d0 40 08 11d+23:13:22.024  READ FPDMA QUEUED
  60 00 28 00 28 00 01 28 44 d8 a0 40 08 11d+23:13:22.024  READ FPDMA QUEUED
  60 00 28 00 b0 00 01 28 44 d4 98 40 08 11d+23:13:22.024  READ FPDMA QUEUED
  60 00 28 00 a8 00 01 28 44 d4 68 40 08 11d+23:13:22.024  READ FPDMA QUEUED
  60 00 28 00 90 00 01 28 44 d5 78 40 08 11d+23:13:22.023  READ FPDMA QUEUED

Error 18 [1] occurred at disk power-on lifetime: 41532 hours (1730 days + 12 hours)
  When the command that caused the error occurred, the device was active or idle.

  After command completion occurred, registers were:
  ER -- ST COUNT  LBA_48  LH LM LL DV DC
  -- -- -- == -- == == == == == == == ==
  84 -- 43 00 00 00 00 00 00 00 00 00 00 00  Error: ICRC, ABRT at LBA = 0x00000000 = 0

  Commands leading to the command that caused the error were:
  CR FEATR COUNT  LBA_48  LH LM LL DV DC  Powered_Up_Time  Command/Feature_Name
  -- == -- -- == == == == -- -- -- -- --  ---------------  --------------------
  60 00 30 00 78 00 01 c1 41 54 c8 40 08     01:19:52.329  READ FPDMA QUEUED
  60 00 28 00 80 00 01 c1 41 54 f8 40 08     01:19:52.329  READ FPDMA QUEUED
  60 00 30 00 70 00 01 c1 41 55 50 40 08     01:19:52.329  READ FPDMA QUEUED
  60 00 28 00 68 00 01 c1 41 54 a0 40 08     01:19:52.326  READ FPDMA QUEUED
  60 00 28 00 60 00 01 c1 41 54 70 40 08     01:19:52.326  READ FPDMA QUEUED

Error 17 [0] occurred at disk power-on lifetime: 41490 hours (1728 days + 18 hours)
  When the command that caused the error occurred, the device was active or idle.

  After command completion occurred, registers were:
  ER -- ST COUNT  LBA_48  LH LM LL DV DC
  -- -- -- == -- == == == == == == == ==
  84 -- 43 00 00 00 00 00 00 00 00 00 00 00  Error: ICRC, ABRT at LBA = 0x00000000 = 0

  Commands leading to the command that caused the error were:
  CR FEATR COUNT  LBA_48  LH LM LL DV DC  Powered_Up_Time  Command/Feature_Name
  -- == -- -- == == == == -- -- -- -- --  ---------------  --------------------
  60 00 b0 00 a0 00 04 19 de dd f8 40 08     00:53:13.589  READ FPDMA QUEUED
  60 00 30 00 38 00 04 19 de dd 70 40 08     00:53:13.588  READ FPDMA QUEUED
  60 00 58 00 a8 00 04 19 de de b0 40 08     00:53:13.588  READ FPDMA QUEUED
  60 00 28 00 b8 00 04 19 de dd a0 40 08     00:53:13.587  READ FPDMA QUEUED
  60 00 b0 00 98 00 04 19 de dc c0 40 08     00:53:13.587  READ FPDMA QUEUED

Error 16 [3] occurred at disk power-on lifetime: 40928 hours (1705 days + 8 hours)
  When the command that caused the error occurred, the device was active or idle.

  After command completion occurred, registers were:
  ER -- ST COUNT  LBA_48  LH LM LL DV DC
  -- -- -- == -- == == == == == == == ==
  84 -- 53 00 00 00 00 00 00 00 00 00 00 00

  Commands leading to the command that caused the error were:
  CR FEATR COUNT  LBA_48  LH LM LL DV DC  Powered_Up_Time  Command/Feature_Name
  -- == -- -- == == == == -- -- -- -- -- --------------- --------------------
  47 00 00 00 01 00 00 00 00 00 12 a0 08  4d+10:19:32.078  READ LOG DMA EXT
  47 00 00 00 01 00 00 00 00 00 00 a0 08  4d+10:19:32.058  READ LOG DMA EXT
  47 00 00 00 01 00 00 00 00 00 13 a0 08  4d+10:19:32.054  READ LOG DMA EXT
  47 00 00 00 01 00 00 00 00 00 00 a0 08  4d+10:19:32.054  READ LOG DMA EXT
  ef 00 10 00 02 00 00 00 00 00 00 a0 08  4d+10:19:32.032  SET FEATURES [Enable SATA feature]

SMART Extended Self-test Log Version: 1 (1 sectors)
Num  Test_Description    Status                  Remaining  LifeTime(hours)  LBA_of_first_error
# 1  Short offline       Completed without error       00%     34980         -
# 2  Short offline       Completed without error       00%     34309         -
# 3  Short offline       Completed without error       00%     33572         -
# 4  Short offline       Completed without error       00%     32828         -
# 5  Short offline       Completed without error       00%     32109         -
# 6  Short offline       Completed without error       00%     31365         -
# 7  Short offline       Completed without error       00%     30645         -
# 8  Extended offline    Completed without error       00%     30289         -
# 9  Short offline       Completed without error       00%     29902         -
#10  Short offline       Completed without error       00%     29159         -
#11  Short offline       Completed without error       00%     28439         -
#12  Short offline       Completed without error       00%     27696         -
#13  Short offline       Completed without error       00%     26977         -
#14  Extended offline    Completed without error       00%     26613         -
#15  Short offline       Completed without error       00%     26233         -
#16  Short offline       Completed without error       00%     25538         -
#17  Short offline       Completed without error       00%     24795         -
#18  Short offline       Completed without error       00%     24052         -
#19  Short offline       Completed without error       00%     23332         -

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
SCT Version (vendor specific):       256 (0x0100)
Device State:                        Active (0)
Current Temperature:                    33 Celsius
Power Cycle Min/Max Temperature:     22/33 Celsius
Lifetime    Min/Max Temperature:     10/57 Celsius
Under/Over Temperature Limit Count:   0/0

SCT Temperature History Version:     2
Temperature Sampling Period:         1 minute
Temperature Logging Interval:        1 minute
Min/Max recommended Temperature:     0/65 Celsius
Min/Max Temperature Limit:           -40/70 Celsius
Temperature History Size (Index):    128 (104)

Index    Estimated Time   Temperature Celsius
 105    2026-10-21 14:37    49  ******************************
 ...    ..(  3 skipped).    ..  ******************************
 109    2026-10-21 14:41    49  ******************************
 110    2026-10-21 14:42    50  *******************************
 111    2026-10-21 14:43    49  ******************************
 112    2026-10-21 14:44    49  ******************************
 113    2026-10-21 14:45    50  *******************************
 114    2026-10-21 14:46    49  ******************************
 115    2026-10-21 14:47    49  ******************************
 116    2026-10-21 14:48    49  ******************************
 117    2026-10-21 14:49    50  *******************************
 ...    ..( 52 skipped).    ..  *******************************
  52    2026-10-21 15:52    50  *******************************
  53    2026-10-21 15:53    51  ********************************
 ...    ..( 26 skipped).    ..  ********************************
  80    2026-10-21 16:20    51  ********************************
  81    2026-10-21 16:21    22  ***
  82    2026-10-21 16:22    23  ****
  83    2026-10-21 16:23    23  ****
  84    2026-10-21 16:24    24  *****
  85    2026-10-21 16:25    26  *******
  86    2026-10-21 16:26    26  *******
  87    2026-10-21 16:27    26  *******
  88    2026-10-21 16:28    27  ********
  89    2026-10-21 16:29    28  *********
  90    2026-10-21 16:30    28  *********
  91    2026-10-21 16:31    29  **********
  92    2026-10-21 16:32    30  ***********
  93    2026-10-21 16:33    30  ***********
  94    2026-10-21 16:34    30  ***********
  95    2026-10-21 16:35    31  ************
  96    2026-10-21 16:36    31  ************
  97    2026-10-21 16:37    31  ************
  98    2026-10-21 16:38    32  *************
 ...    ..(  2 skipped).    ..  *************
 101    2026-10-21 16:41    32  *************
 102    2026-10-21 16:42    33  **************
 103    2026-10-21 16:43    33  **************
 104    2026-10-21 16:44    49  ******************************

SCT Error Recovery Control:
           Read:     70 (7.0 seconds)
          Write:     70 (7.0 seconds)

Device Statistics (GP Log 0x04)
Page  Offset Size        Value Flags Description
0x01  =====  =               =  ===  == General Statistics (rev 1) ==
0x01  0x008  4             287  ---  Lifetime Power-On Resets
0x01  0x010  4           46428  ---  Power-on Hours
0x01  0x018  6    688800648896  ---  Logical Sectors Written
0x01  0x020  6      1605536207  ---  Number of Write Commands
0x01  0x028  6    915501665203  ---  Logical Sectors Read
0x01  0x030  6      4651026580  ---  Number of Read Commands
0x01  0x038  6    167142934300  ---  Date and Time TimeStamp
0x03  =====  =               =  ===  == Rotating Media Statistics (rev 1) ==
0x03  0x008  4           40922  ---  Spindle Motor Power-on Hours
0x03  0x010  4           40922  ---  Head Flying Hours
0x03  0x018  4            1868  ---  Head Load Events
0x03  0x020  4               0  ---  Number of Reallocated Logical Sectors
0x03  0x028  4               0  ---  Read Recovery Attempts
0x03  0x030  4               0  ---  Number of Mechanical Start Failures
0x04  =====  =               =  ===  == General Errors Statistics (rev 1) ==
0x04  0x008  4               0  ---  Number of Reported Uncorrectable Errors
0x04  0x010  4              17  ---  Resets Between Cmd Acceptance and Completion
0x05  =====  =               =  ===  == Temperature Statistics (rev 1) ==
0x05  0x008  1              33  ---  Current Temperature
0x05  0x010  1              48  N--  Average Short Term Temperature
0x05  0x018  1              48  N--  Average Long Term Temperature
0x05  0x020  1              57  ---  Highest Temperature
0x05  0x028  1              10  ---  Lowest Temperature
0x05  0x030  1              56  N--  Highest Average Short Term Temperature
0x05  0x038  1              25  N--  Lowest Average Short Term Temperature
0x05  0x040  1              49  N--  Highest Average Long Term Temperature
0x05  0x048  1              25  N--  Lowest Average Long Term Temperature
0x05  0x050  4               0  ---  Time in Over-Temperature
0x05  0x058  1              65  ---  Specified Maximum Operating Temperature
0x05  0x060  4               0  ---  Time in Under-Temperature
0x05  0x068  1               0  ---  Specified Minimum Operating Temperature
0x06  =====  =               =  ===  == Transport Statistics (rev 1) ==
0x06  0x008  4            1004  ---  Number of Hardware Resets
0x06  0x010  4             140  ---  Number of ASR Events
0x06  0x018  4              19  ---  Number of Interface CRC Errors
0x07  =====  =               =  ===  == Solid State Device Statistics (rev 1) ==
                                |||_ C monitored condition met
                                ||__ D supports DSN
                                |___ N normalized value

Pending Defects log (GP Log 0x0c)
No Defects Logged

SATA Phy Event Counters (GP Log 0x11)
ID      Size     Value  Description
0x0001  2            0  Command failed due to ICRC error
0x0002  2            0  R_ERR response for data FIS
0x0003  2            0  R_ERR response for device-to-host data FIS
0x0004  2            0  R_ERR response for host-to-device data FIS
0x0005  2            0  R_ERR response for non-data FIS
0x0006  2            0  R_ERR response for device-to-host non-data FIS
0x0007  2            0  R_ERR response for host-to-device non-data FIS
0x0008  2            0  Device-to-host non-data FIS retries
0x0009  2            2  Transition from drive PhyRdy to drive PhyNRdy
0x000a  2            1  Device-to-host register FISes sent due to a COMRESET
0x000b  2            0  CRC errors within host-to-device FIS
0x000d  2            0  Non-CRC errors within host-to-device FIS
```
