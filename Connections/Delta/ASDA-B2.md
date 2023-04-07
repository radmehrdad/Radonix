# Connection between Radonix Contollers and Two DELTA ASDA-B2

This guide will help you connect Radonix Controllers to two DELTA ASDA-B2.

## Connection Table

| RadonixPC (DB15F) | ASDA-B (DB25F) | ADSA-B2 (1,2) Pins |
| ----------------- | -------------- | ------------------ |
| 1                 | 11 (1,2)       | VCC +24 V          |
| 2                 | 37 (1,2)       | Direction -        |
| 3                 | 39 (1,2)       | Direction +        |
| 4                 | 41 (1,2)       | Pulse -            |
| 5                 | 43 (1,2)       | Pulse +            |
| 6                 | 9 (1,2)        | Servo On           |
| 7                 | 7 (1)          | Ready              |
| 8                 | 44 (1,2)       | Encoder Zero       |
| 9                 | 33 (1,2)       | Reset              |
| 10                | 32 (1,2)       | Alarm              |
| 11                | 31 (1,2)       | Ground             |
| 12                | 30 (1,2)       | Ground             |
| 13                | 19 (1,2)       | Ground             |
| 14                | 6 (2)          | Ground             |
| 15                | 14 (1,2)       | Ground             |

## Connection Sequence for Ready Pins

1. Connect Controller-P7 to Driver (1)-P7
2. Connect Driver (1)-P6 to Driver (2)-P7
3. Connect Driver (2)-P6 to Controller-P14

## Support & Contact Information

If you encounter any issues or have questions, feel free to reach out to us via email at Mehrdadrad@gmail.com / Arsprnp@gmail.com or through our social media channels.

## License

© Radonix 2023. All Rights Reserved.
