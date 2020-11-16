# 5 Stages of Pen Testing
1. Reconnaissance and Information Gathering
2. Scanning
3. Gaining Access / Exploitation
4. Maintaining Access
5. Covering Tracks

## Reconnaissance & Information Gathering
- This is the only step that you can perform on any website/target that you want, since gathering information is not illegal
- Directly and Passively: interacting with the target or not

## Scanning
- Here is where you can start getting in trouble if you don't have permissions
- Finding openings in target systems
  - Gateways, open ports, systems the target runs
  - Vulnerability scanning

## Gaining Access / Exploitation
- Step where we actually hack the target using info gathered in phase 1 and phase 2
- Allows us to steal data from system or to use the devices to attack other devices on the same network
- Usually can consider the pen test successful at this point

## Maintaining Access
- You might not always need you to perform this step as client may only care if the system is penetrable or not
- Important step and commonly done by installing backdoors and rootkits
  - Allows us to get back into device without having to hack it again

## Covering Tracks
- Removing all evidence than an attack ever took place
- Deleting/hiding files
- Clearing logs
- Reverting system changes that occurred while the attack took place
