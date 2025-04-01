# download arudion ide
# add the grbl folder as a library
# file -> examples -> grbl -> grbl upload
# connect your uno and upload code
# open ugsplatform-win\bin\ugsplatform64.exe
# connect on usb port with 115200 baud

# enjoy!!

default values::
***********************
*** Connecting to jserialcomm://COM3:115200
Grbl 1.1h ['$' for help]
*** Fetching device status
>>> ?
<Idle|MPos:0.000,0.000,0.000|FS:0,0|WCO:-0.564,0.000,0.000>
ok
*** Fetching device version
>>> $I
[VER:1.1h.20190830:G21G91X-0.2F300]
[OPT:V,15,128]
ok
*** Fetching device settings
>>> $$
$0 = 10    (Step pulse time, microseconds)
$1 = 25    (Step idle delay, milliseconds)
$2 = 0    (Step pulse invert, mask)
$3 = 0    (Step direction invert, mask)
$4 = 0    (Invert step enable pin, boolean)
$5 = 0    (Invert limit pins, boolean)
$6 = 0    (Invert probe pin, boolean)
$10 = 1    (Status report options, mask)
$11 = 0.010    (Junction deviation, millimeters)
$12 = 0.002    (Arc tolerance, millimeters)
$13 = 0    (Report in inches, boolean)
$20 = 0    (Soft limits enable, boolean)
$21 = 0    (Hard limits enable, boolean)
$22 = 0    (Homing cycle enable, boolean)
$23 = 0    (Homing direction invert, mask)
$24 = 25.000    (Homing locate feed rate, mm/min)
$25 = 500.000    (Homing search seek rate, mm/min)
$26 = 250    (Homing switch debounce delay, milliseconds)
$27 = 1.000    (Homing switch pull-off distance, millimeters)
$30 = 1000    (Maximum spindle speed, RPM)
$31 = 0    (Minimum spindle speed, RPM)
$32 = 0    (Laser-mode enable, boolean)
$100 = 250.000    (X-axis travel resolution, step/mm)
$101 = 250.000    (Y-axis travel resolution, step/mm)
$102 = 250.000    (Z-axis travel resolution, step/mm)
$110 = 500.000    (X-axis maximum rate, mm/min)
$111 = 500.000    (Y-axis maximum rate, mm/min)
$112 = 500.000    (Z-axis maximum rate, mm/min)
$120 = 10.000    (X-axis acceleration, mm/sec^2)
$121 = 10.000    (Y-axis acceleration, mm/sec^2)
$122 = 10.000    (Z-axis acceleration, mm/sec^2)
$130 = 200.000    (X-axis maximum travel, millimeters)
$131 = 200.000    (Y-axis maximum travel, millimeters)
$132 = 200.000    (Z-axis maximum travel, millimeters)
ok
*** Fetching device state
>>> $G
[GC:G0 G54 G17 G21 G90 G94 M5 M9 T0 F0 S0]
ok
*** Connected to GRBL 1.1h
>>> $102=1000.0
ok
>>> G10 P0 L20 X0.564Y0Z0
*** Canceling current stream
Grbl 1.1h ['$' for help]
Error while processing response <ok>: An unexpected command was completed by the controller.
>>> $102=500.0
ok
>>> G10 P0 L20 X0.564Y0Z0
Grbl 1.1h ['$' for help]
ok
>>> $102=250.0
ok
>>> G10 P0 L20 X0.564Y0Z0
Grbl 1.1h ['$' for help]
ok
