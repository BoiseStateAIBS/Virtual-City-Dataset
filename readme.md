## Boise State Virtual City Cybersecurity Dataset
Network logs are collected using Zeek( previously bro) in Security Onion for seven days from September 1, 2024, to September 7, 2024. Penetration tests on the network were carried out on three separate days, starting on September 4 and ending on September 6, lasting from 5 PM MST to 9 PM MST each day. Following are different types of zeek logs collected by the system. These logs were recorded:


- Broker logs
- Capture loss
- Conn summary
- Conn logs
- Dhcp
- DNS logs
- Ecat arp logs
- Enip logs
- Notice
- Stats
- Weird

## Instruction 
1. Use `process_raw_zeek_log.ipynb` notebook to get tain data (benign.csv) and test data (malacious.csv)
2. Use `process_attacks.ipynb` notebook to get all_attacks.csv which has attacks and their corresponding details
3. Use `assign_labelipynb` notebook to assign label to each events and produce training and test dataset for [CAPTOR](https://github.com/BoiseStateAIBS/CAPTOR)

## Acknowledgement
This research was funded by a National Centers of Academic Excellence in Cybersecurity grant H98230-22-1-0300, which is part of the National Security Agency.