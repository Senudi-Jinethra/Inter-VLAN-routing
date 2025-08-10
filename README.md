# Inter-VLAN-routing
Inter-VLAN routing is used to establish communication between several VLANs. There are three types of VLANs availble. They are physical cabling, router-on-a-stick (ROAS), and switch virtual interfaces (SVI).

## 01 Router-on-a-stick (ROAS)
- Add a router
  <img width="1920" height="977" alt="Screenshot (504)" src="https://github.com/user-attachments/assets/c07e145a-75c1-4049-84ab-8f68ea388167" />

- Then, trunk the port in the relevant switch
<img width="1049" height="317" alt="Screenshot (505)" src="https://github.com/user-attachments/assets/40c43118-082f-47e9-84a7-837eacccdbbc" />

- Next, turn on the port in the router
<img width="1049" height="386" alt="Screenshot (506)" src="https://github.com/user-attachments/assets/4a7abbfb-f5e5-45c9-9abc-2875d21e52d9" />

- Next, create the sub-interfaces that you want in the router
<img width="1046" height="818" alt="Screenshot (507)" src="https://github.com/user-attachments/assets/6bf2d4b1-6610-446d-9fb3-d2e7f1d90d15" />

