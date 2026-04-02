# HA-modbus-Adlar-aurora-Pro-III
Package for connecting home assistant and Adlar Aurora Pro III Heatpump through Modbus

##Configuration

Add the following lines to you configuration.yaml

homeassistant:
  packages: !include_dir_named packages

### Waveshare Setttings: 

Mode: Modbus TCP ==> Modbus RTU 

- Baudrate: 9600
- Databits: 8
- Parity: none
- Stop: 2
- Baudrate adaptive (RFC2117): Disable

to be continued

