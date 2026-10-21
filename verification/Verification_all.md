## Ping Verifications

| Device | Building | | Department | VLAN | Ping Address | Verification |
|--------|----------|-|------------|------|--------------|--------------|
| PC0 | A | -> | Finance | 110 | 10.0.110.12 |  <img src="./VLAN_Pings/VLAN_10_Finance-A_to_Building_B/PC_FinanceA_to_PC_Finance_B.JPG" alt="Ping" width="650"> |
| PC0 | A | -> | Engineering | 120 | 10.0.120.12 | <img src="./VLAN_Pings/VLAN_10_Finance-A_to_Building_B/PC_FinanceA_to_PC_Engineering_B.JPG" alt="ping" width="650"> |
| PC0 | A | -> | HR | 130 | 10.0.130.10 |  <img src="./VLAN_Pings/VLAN_10_Finance-A_to_Building_B/PC_FinanceA_to_PC_HR_B.JPG" alt="ping" width="650"> |
| PC0 | A | -> | Management | 199 | 10.0.199.11 | <img src="./VLAN_Pings/VLAN_10_Finance-A_to_Building_B/PC_FinanceA_to_PC_Management_B.JPG" alt="ping" width="650"> |
| PC2 | A | -> | Finance | 110 | 10.0.110.12 | <img src="./VLAN_Pings/VLAN_20_Engineering-A_to_Building_B/PC_EngineeringA_to_PC_Finance_B.JPG" alt="ping" width="650"> |
| PC2 | A | -> | Engineering | 120 | 10.0.120.12 | <img src="./VLAN_Pings/VLAN_20_Engineering-A_to_Building_B/PC_EngineeringA_to_PC_Engineering_B.JPG" alt="ping" width="650"> |
| PC2 | A | -> | HR | 130 | 10.0.130.10 | <img src="./VLAN_Pings/VLAN_20_Engineering-A_to_Building_B/PC_EngineeringA_to_PC_HR_B.JPG" alt="ping" width="650"> |
| PC2 | A | -> | Management | 199 | 10.0.199.11 | <img src="./VLAN_Pings/VLAN_20_Engineering-A_to_Building_B/PC_EngineeringA_to_PC_Management_B.JPG" alt="ping" width="650"> |
| PC4 | A | -> | Finance | 110 | 10.0.110.12 | <img src="./VLAN_Pings/VLAN_30_HR-A_to_Building_B/PC_HR_A_to_PC_Finance_B.JPG" alt="ping" width="650"> |
| PC4 | A | -> | Engineering | 120 | 10.0.120.12 | <img src="./VLAN_Pings/VLAN_30_HR-A_to_Building_B/PC_HR_A_to_PC_Engineering_B.JPG" alt="ping" width="650"> |
| PC4 | A | -> | HR | 130 | 10.0.130.10 | <img src="./VLAN_Pings/VLAN_30_HR-A_to_Building_B/PC_HR_A_to_PC_HR_B.JPG" alt="ping" width="650"> |
| PC4 | A | -> | Management | 199 | 10.0.199.11 | <img src="./VLAN_Pings/VLAN_30_HR-A_to_Building_B/PC_HR_A_to_PC_Management_B.JPG" alt="ping" width="650"> |
| PC6 | A | -> | Finance | 110 | 10.0.110.12 | <img src="./VLAN_Pings/VLAN_99_Management-A_to_Building_B/PC_ManagementA_to_PC_Finance_B.JPG" alt="ping" width="650"> |
| PC6 | A | -> | Engineering | 120 | 10.0.120.12 | <img src="./VLAN_Pings/VLAN_99_Management-A_to_Building_B/PC_ManagementA_to_PC_Engineering_B.JPG" alt="ping" width="650"> |
| PC6 | A | -> | HR | 130 | 10.0.130.10 | <img src="./VLAN_Pings/VLAN_99_Management-A_to_Building_B/PC_ManagementA_to_PC_HR_B.JPG" alt="ping" width="650"> |
| PC6 | A | -> | Management | 199 | 10.0.199.11 | <img src="./VLAN_Pings/VLAN_99_Management-A_to_Building_B/PC_ManagementA_to_PC_Management_B.JPG" alt="ping" width="650"> |
| | | | | | | |

## DHCP Release Verifications
| VLAN | Subnet | Verification | 
|------|--------|--------------|
| 10 | 10.0.10.0/24 | <img src="./DHCP_Release_Renew/VLAN10_FinanceA.JPG" alt="ping" width="650"> |
| 20 | 10.0.20.0/24 | <img src="./DHCP_Release_Renew/VLAN20_EngineeringA.JPG" alt="ping" width="650"> |
| 30 | 10.0.30.0/24 | <img src="./DHCP_Release_Renew/VLAN30_HR_A.JPG" alt="ping" width="650"> |
| 99 | 10.0.99.0/24 | <img src="./DHCP_Release_Renew/VLAN99_ManagementA.JPG" alt="ping" width="650"> |
| 110 | 10.0.110.0/24 | <img src="./DHCP_Release_Renew/VLAN110_FinanceB.JPG" alt="ping" width="650"> |
| 120 | 10.0.120.0/24 | <img src="./DHCP_Release_Renew/VLAN120_EngineeringB.JPG" alt="ping" width="650"> |
| 130 | 10.0.130.0/24 | <img src="./DHCP_Release_Renew/VLAN130_HR_B.JPG" alt="ping" width="650"> |
| 199 | 10.0.199.0/24 | <img src="./DHCP_Release_Renew/VLAN199_ManagementB.JPG" alt="ping" width="650"> |
| | | |