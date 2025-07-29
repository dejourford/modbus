# Modbus Write Command Detection in Industrical Network Traffic

<img src="images/hero.png" alt="hero" width=600/><br />


## Purpose

The purpose of this lab is to simulate a realistic OT (Operational Technology) incident detection scenario by analyzing Modbus/TCP network traffic for unauthorized Write Multiple Register (Function Code 16) commands. This exercise reinforces protocol-level understanding of Modbus, teaches how to filter and interpret packet captures in Wireshark, and highlights how unauthorized writes to PLC registers can result in unsafe or unexpected changes to industrial processes.


## Procedure


Download `pcap`	file from <a href="https://github.com/ITI/ICS-Security-Tools/blob/master/pcaps/ModbusTCP/modbus_test_data_part1.pcap">Tim Yardley's ICS-Security-Tools</a>

Open file in Wireshark

<img src="images/file.png" alt="open file" width=600/><br />

Add filter to only display modbus traffic

<img src="images/filter.png" alt="apply filter" width=600/><br />

Analyze captures



## Discussion


## Planned Improvements 

