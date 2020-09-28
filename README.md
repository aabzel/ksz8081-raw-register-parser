# ksz8081-raw-register-parser
ksz8081 raw register value blob parser
ksz8081 binary register value blob parser (interpreter)

That is a utility tool to interpret the raw binary ksz8081 registers values blob to human readable *.txt configuration report according the ksz8081 datasheet. As a example there are data-in and data-out for ksz8081 *.txt. Users all over the world may appreciate that diagnostic tool and such support of ksz8081.

1) The ksz8081 registers values themselves must be read from ksz8081 chip via 2-wire MDIO bus to MCU RAM.
2) Then binary blob must be transfered from MCU RAM to PC disc (in txt file) via UART,RS232, 100-Base-TX, Bluetooth, WiFi, CAN or any other interface.
3) Finaly on PC that utility can instantly interpret chip settings and reveal honest ksz8081 configuration.

Thus developers will get the entire bird's eye view representation of chip configuration.

That is a very handy tool for diagnostic and bug search.
