# OSPF & Static IP Addressing Lab

## Lab Overview
This lab focuses on configuring a routed network using static IP addressing and OSPF routing. The goal is to establish full connectivity across the topology while practicing proper router and switch configuration techniques.

---

# Objectives

- Configure static IPv4 addressing on all devices
- Configure OSPF routing between routers
- Advertise connected networks using OSPF
- Verify neighbor adjacencies
- Ensure full end-to-end connectivity
- Configure hostnames on all devices
- Shutdown unused switch ports
- Practice troubleshooting connectivity issues
---

# Topology Information
<img width="1520" height="677" alt="image" src="https://github.com/user-attachments/assets/2d81e683-b92b-4d47-a685-f863cee80aec" />

# PC Addressing Table 
<img width="712" height="262" alt="image" src="https://github.com/user-attachments/assets/55fe17b0-c70a-47c1-b533-02e29e9130e8" />

#Router Interface Table Breakdown
<img width="706" height="360" alt="image" src="https://github.com/user-attachments/assets/af228d70-687d-483a-a3f8-90b4d1594db4" />

---

# Verification Tools 

```bash
show ip interface brief
show ip route
show running-config
show ip ospf neighbor
show ip protocols

