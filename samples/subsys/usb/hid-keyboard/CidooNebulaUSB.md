```
0x1C,              // Unknown (bTag: 0x01, bType: 0x03)
0x00,              // Unknown (bTag: 0x00, bType: 0x00)
0x60,              // Unknown (bTag: 0x06, bType: 0x00)
0x8A, 0xC8, 0xD8,  // String Minimum (-10040)
0x0B, 0xA3, 0xFF, 0xFF, 0x00,  // Usage (0xFFFFA3)
0x00,              // Unknown (bTag: 0x00, bType: 0x00)
0x00,              // Unknown (bTag: 0x00, bType: 0x00)
0x00,              // Unknown (bTag: 0x00, bType: 0x00)
0x08,              // Usage
0x00,              // Unknown (bTag: 0x00, bType: 0x00)
0x01, 0x01,        // Unknown (bTag: 0x00, bType: 0x00)
0x00,              // Unknown (bTag: 0x00, bType: 0x00)
0x11, 0x00,        // Unknown (bTag: 0x01, bType: 0x00)
0x80,              // Input
0x02, 0x4F, 0x00,  // Unknown (bTag: 0x00, bType: 0x00)
0x00,              // Unknown (bTag: 0x00, bType: 0x00)
0x00,              // Unknown (bTag: 0x00, bType: 0x00)
0x03, 0x05, 0x01, 0x09, 0x06,  // Unknown (bTag: 0x00, bType: 0x00)
0xA1, 0x01,        // Collection (Application)
0x05, 0x07,        //   Usage Page (Kbrd/Keypad)
0x19, 0xE0,        //   Usage Minimum (0xE0)
0x29, 0xE7,        //   Usage Maximum (0xE7)
0x15, 0x00,        //   Logical Minimum (0)
0x25, 0x01,        //   Logical Maximum (1)
0x75, 0x01,        //   Report Size (1)
0x95, 0x08,        //   Report Count (8)
0x81, 0x02,        //   Input (Data,Var,Abs,No Wrap,Linear,Preferred State,No Null Position)
0x95, 0x01,        //   Report Count (1)
0x75, 0x08,        //   Report Size (8)
0x81, 0x01,        //   Input (Const,Array,Abs,No Wrap,Linear,Preferred State,No Null Position)
0x95, 0x05,        //   Report Count (5)
0x75, 0x01,        //   Report Size (1)
0x05, 0x08,        //   Usage Page (LEDs)
0x19, 0x01,        //   Usage Minimum (Num Lock)
0x29, 0x05,        //   Usage Maximum (Kana)
0x91, 0x02,        //   Output (Data,Var,Abs,No Wrap,Linear,Preferred State,No Null Position,Non-volatile)
0x95, 0x01,        //   Report Count (1)
0x75, 0x03,        //   Report Size (3)
0x91, 0x01,        //   Output (Const,Array,Abs,No Wrap,Linear,Preferred State,No Null Position,Non-volatile)
0x95, 0x06,        //   Report Count (6)
0x75, 0x08,        //   Report Size (8)
0x15, 0x00,        //   Logical Minimum (0)
0x26, 0xFF, 0x00,  //   Logical Maximum (255)
0x05, 0x07,        //   Usage Page (Kbrd/Keypad)
0x19, 0x00,        //   Usage Minimum (0x00)
0x2A, 0xFF, 0x00,  //   Usage Maximum (0xFF)
0x81, 0x00,        //   Input (Data,Array,Abs,No Wrap,Linear,Preferred State,No Null Position)
0x05, 0x0C,        //   Usage Page (Consumer)
0x09, 0x00,        //   Usage (Unassigned)
0x15, 0x80,        //   Logical Minimum (-128)
0x25, 0x7F,        //   Logical Maximum (127)
0x95, 0x40,        //   Report Count (64)
0x75, 0x08,        //   Report Size (8)
0xB1, 0x02,        //   Feature (Data,Var,Abs,No Wrap,Linear,Preferred State,No Null Position,Non-volatile)
0xC0,              // End Collection

// 107 bytes

```

From here: http://eleccelerator.com/usbdescreqparser/#

```
Frame 251: 30 bytes on wire (240 bits), 30 bytes captured (240 bits) on interface \\.\USBPcap1, id 0
USB URB
HID Data: 03e900
    Report ID: 0x03
    Array: e900
        0000 0000  1110 1001 = Usage: Volume Increment (0x000c, 0x00e9)
```

```
Frame 259: 30 bytes on wire (240 bits), 30 bytes captured (240 bits) on interface \\.\USBPcap1, id 0
USB URB
HID Data: 03e200
    Report ID: 0x03
    Array: e200
        0000 0000  1110 0010 = Usage: Mute (0x000c, 0x00e2)

```
