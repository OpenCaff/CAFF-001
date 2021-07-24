# CAFF-001 by OpenCaff is to regulate the APIs of smart coffee makers and make them interoperate. We will have new revisions
# CAFF-001 r1.02
## programming
### all mass-produced smart coffee makers verified by OpenCaff must report using Python with different variables or use HTCPCP(Python variable under this text:
- 'ct' is "coffee temperature"
- 'io' is for remote brewing and 0 = stop/idle while 1=start/continue
- 'pl' is for controlling the hot plate 0 is off/idle while 1 = start/continue (It must be 1 while brewing)
- This part could be substituted by HTCPCP(https://en.wikipedia.org/wiki/Hyper_Text_Coffee_Pot_Control_Protocol)
## Communication
### all common devices must have a way to communicate with the brewer directly:
- the machine must have a way to physically communicate
- If it runs online, it must use a local web server with all the data saved
- It must be able to communicate via BlueTooth and wifi when offline or online
- It must be able to save profiles.
- It must be tweakable (unlocked firmware, easy to code with, No EULA that does not restrict any hack by the main person)
## Data collection
### we will have strong data collection standards
- It must not share any data to any central server or to any gov, advertiser, company, etc.
## Openness
- everything about said maker must be on the website(schematic, parts, code, etc.) with detailed explanation.
