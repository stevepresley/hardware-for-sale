WDC WD101EFBX-68B0AN0 | 10 TB, 7200 rpm
Serial: VCHN0NLP
Power-on hours: 32,831 | SMART: PASSED
Reallocated / pending / offline-uncorrectable sectors: 0 / 0 / 0
UDMA CRC errors: 1; error log records an ICRC/ABRT interface error
SMART capture time: 2026-10-21 20:44 UTC

**Captured SMART report** (command: `smartctl -x`):

```text
smartctl 7.4 2023-08-01 r5530 [x86_64-linux-6.6.44-production+truenas] (local build)
Copyright (C) 2002-23, Bruce Allen, Christian Franke, www.smartmontools.org

=== START OF INFORMATION SECTION ===
Model Family:     Western Digital Red Plus
Device Model:     WDC WD101EFBX-68B0AN0
Serial Number:    VCHN0NLP
LU WWN Device Id: 5 000cca 0b0d7316b
Firmware Version: 85.00A85
User Capacity:    10,000,831,348,736 bytes [10.0 TB]
Sector Sizes:     512 bytes logical, 4096 bytes physical
Rotation Rate:    7200 rpm
Form Factor:      3.5 inches
Local Time is:    Wed Oct 21 16:44:20 2026 EDT
SMART support is: Available - device has SMART capability.
SMART support is: Enabled

=== START OF READ SMART DATA SECTION ===
SMART overall-health self-assessment test result: PASSED

SMART Attributes:
  1 Raw_Read_Error_Rate          100/100/016  raw 0
  2 Throughput_Performance       128/128/054  raw 108
  3 Spin_Up_Time                 145/145/024  raw 538 (Average 582)
  4 Start_Stop_Count             100/100/000  raw 514
  5 Reallocated_Sector_Ct        100/100/005  raw 0
  7 Seek_Error_Rate              100/100/067  raw 0
  8 Seek_Time_Performance        128/128/020  raw 18
  9 Power_On_Hours               096/096/000  raw 32831
 10 Spin_Retry_Count             100/100/060  raw 0
 12 Power_Cycle_Count            100/100/000  raw 64
192 Power-Off_Retract_Count      098/098/000  raw 2414
193 Load_Cycle_Count              098/098/000  raw 2414
194 Temperature_Celsius           180/180/000  raw 36 (Min/Max 17/59)
196 Reallocated_Event_Count       100/100/000  raw 0
197 Current_Pending_Sector        100/100/000  raw 0
198 Offline_Uncorrectable         100/100/000  raw 0
199 UDMA_CRC_Error_Count          200/200/000  raw 1

SMART Extended Comprehensive Error Log:
Device Error Count: 1
Error: ICRC, ABRT at LBA = 0x00000000 = 0

SMART Extended Self-test Log:
No self-tests have been logged.

SCT Status:
Current Temperature: 36 Celsius
Lifetime Min/Max Temperature: 17/59 Celsius
Specified Max Operating Temperature: 65 Celsius

Device Statistics:
Power-on Hours: 32831
Reallocated Logical Sectors: 0
Reported Uncorrectable Errors: 0
Interface CRC Errors: 1
```
