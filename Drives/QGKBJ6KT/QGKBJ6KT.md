WDC WD140EFFX-68VBXN0 | 14 TB | 5,400 rpm
Serial: QGKBJ6KT
Power-on hours: 41,334 | SMART: PASSED
Reallocated: 0 | Pending: 0 | Offline uncorrectable: 0

**Full captured report*** (command: `smartctl -a -d sat /dev/sda`; preserving the complete output supplied):

```text
smartctl 6.5 (build date Mar  2 2021) [x86_64-linux-4.4.59+] (local build)
Copyright (C) 2002-16, Bruce Allen, Christian Franke, www.smartmontools.org

=== START OF INFORMATION SECTION ===
Model Family:     Red
Device Model:     WDC WD140EFFX-68VBXN0
Serial Number:    QGKBJ6KT
LU WWN Device Id: 5 000cca 29bef8373
Firmware Version: 81.00A81
User Capacity:    14,000,519,643,136 bytes [14.0 TB]
Sector Sizes:     512 bytes logical, 4096 bytes physical
Rotation Rate:    5400 rpm
Form Factor:      3.5 inches
Device is:        In smartctl database [for details use: -P show]
ATA Version is:   ACS-2, ATA8-ACS T13/1699-D revision 4
SATA Version is:  SATA 3.2, 6.0 Gb/s (current: 6.0 Gb/s)
Local Time is:    Mon Oct  5 10:31:20 2026 -05
SMART support is: Available - device has SMART capability.
SMART support is: Enabled

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
data collection:                (  101) seconds.
Offline data collection
capabilities:                    (0x5b) SMART execute Offline immediate.
                                        Auto Offline data collection on/off support.
                                        Suspend Offline collection upon new
                                        command.
                                        Offline surface scan supported.
                                        Self-test supported.
                                        No Conveyance Self-test supported.
                                        Selective Self-test supported.
SMART capabilities:            (0x0003) Saves SMART data before entering
                                        power-saving mode.
                                        Supports SMART auto save timer.
Error logging capability:        (0x01) Error logging supported.
General Purpose Logging supported.
Short self-test routine
recommended polling time:        (   2) minutes.
Extended self-test routine
recommended polling time:        (1516) minutes.
SCT capabilities:              (0x003d) SCT Status supported.
                                        SCT Error Recovery Control supported.
                                        SCT Feature Control supported.
                                        SCT Data Table supported.

SMART Attributes Data Structure revision number: 16
Vendor Specific SMART Attributes with Thresholds:
ID# ATTRIBUTE_NAME                                                   FLAG     VALUE WORST THRESH TYPE      UPDATED  WHEN_FAILED RAW_VALUE
  1 Raw_Read_Error_Rate                                              0x000b   100   100   001    Pre-fail  Always       -       0
  2 Throughput_Performance                                           0x0004   135   135   054    Old_age   Offline      -       108
  3 Spin-up_Time                                                     0x0007   081   081   001    Pre-fail  Always       -       30089675133
  4 Start/Stop_Count                                                 0x0012   100   100   000    Old_age   Always       -       291
  5 Re-allocated_Sector_Count                                        0x0033   100   100   001    Pre-fail  Always       -       0
  7 Seek_Error_Rate                                                  0x000a   100   100   001    Old_age   Always       -       0
  8 Seek_Time_Performance                                            0x0004   133   133   020    Old_age   Offline      -       18
  9 Power-on_Hours_Count                                             0x0012   095   095   000    Old_age   Always       -       41334
 10 Spin_Retry_Count                                                 0x0012   100   100   001    Old_age   Always       -       0
 12 Drive_Power_Cycle_Count                                          0x0032   096   096   000    Old_age   Always       -       291
 22 Internal_Environment_Status_(Helium_Status)                      0x0023   100   100   025    Pre-fail  Always       -       100
192 Power_Off_Retract_Count                                          0x0032   100   100   000    Old_age   Always       -       1821
193 Load/Unload_Cycles                                               0x0012   100   100   000    Old_age   Always       -       1821
194 Temperature                                                      0x0002   045   045   000    Old_age   Always       -       36 (Min/Max 14/47)
196 Relocation_Event_Count                                           0x0032   100   100   000    Old_age   Always       -       0
197 Current_Pending_Sector_Count                                     0x0022   100   100   000    Old_age   Always       -       0
198 Off-Line_Scan_Uncorrectable_Sector_Count                         0x0008   100   100   000    Old_age   Offline      -       0
199 Ultra_DMA_CRC_Error_Count/Frame_Error_Count                      0x000a   100   100   000    Old_age   Always       -       0

SMART Error Log Version: 1
No Errors Logged

SMART Self-test log structure revision number 1
Num  Test_Description    Status                  Remaining  LifeTime(hours)  LBA_of_first_error
# 1  Short offline       Completed without error       00%     41131         -
# 2  Short offline       Completed without error       00%     40388         -
# 3  Short offline       Completed without error       00%     39645         -
# 4  Short offline       Completed without error       00%     38926         -
# 5  Short offline       Completed without error       00%     38183         -
# 6  Short offline       Completed without error       00%     37734         -
# 7  Short offline       Completed without error       00%     37463         -
# 8  Extended offline    Aborted by host               10%     37182         -
# 9  Short offline       Completed without error       00%     36720         -
#10  Short offline       Completed without error       00%     36049         -
#11  Short offline       Completed without error       00%     35305         -
#12  Short offline       Completed without error       00%     34562         -
#13  Short offline       Completed without error       00%     33843         -
#14  Short offline       Completed without error       00%     33099         -
#15  Extended offline    Aborted by host               10%     32819         -
#16  Short offline       Completed without error       00%     32380         -
#17  Short offline       Completed without error       00%     31637         -
#18  Short offline       Completed without error       00%     30893         -
#19  Short offline       Completed without error       00%     30174         -
#20  Short offline       Completed without error       00%     29431         -
#21  Short offline       Completed without error       00%     28712         -

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
```
