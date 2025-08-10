# Inter-VLAN-routing
Inter-VLAN routing is used to establish communication between several VLANs. There are three types of VLANs availble. They are physical cabling, router-on-a-stick (ROAS), and switch virtual interfaces (SVI).

## 01 Router-on-a-stick (ROAS)
- Add a router
  <img width="1920" height="977" alt="Screenshot (504)" src="https://github.com/user-attachments/assets/c07e145a-75c1-4049-84ab-8f68ea388167" />

- Then, trunk the port in the relevant switch. Trunking brings multiple VLANs on to one connection.
<img width="1049" height="317" alt="Screenshot (505)" src="https://github.com/user-attachments/assets/40c43118-082f-47e9-84a7-837eacccdbbc" />

- Next, turn on the port in the router
<img width="1049" height="386" alt="Screenshot (506)" src="https://github.com/user-attachments/assets/4a7abbfb-f5e5-45c9-9abc-2875d21e52d9" />

- Next, create the sub-interfaces that you want in the router
<img width="1046" height="818" alt="Screenshot (507)" src="https://github.com/user-attachments/assets/6bf2d4b1-6610-446d-9fb3-d2e7f1d90d15" />

## 02 Switch virtual interfaces (SVI)
- Here, we use a multilayer switch
  <img width="1294" height="713" alt="Screenshot (508)" src="https://github.com/user-attachments/assets/34ac7ddf-ac14-480b-9f4f-8e4336ed6185" />

- Then create the VLANs and assign ports to them
<img width="1051" height="677" alt="Screenshot (509)" src="https://github.com/user-attachments/assets/a777a431-9b6e-4133-b465-e1b925fe61f5" />

<img width="1045" height="574" alt="Screenshot (510)" src="https://github.com/user-attachments/assets/279c91d7-1c23-4977-bf78-59b996abb4c0" />

- Then, do the inter-VLAN routing
<img width="1048" height="528" alt="Screenshot (511)" src="https://github.com/user-attachments/assets/79fd0df6-0e2a-4720-8c87-073f6d6d06f0" />

- Finally, enable routing on the layer 3 switch
<img width="1051" height="329" alt="Screenshot (512)" src="https://github.com/user-attachments/assets/e4e3ae1e-1ee6-4a20-a7f2-7aa8a45d42b2" />
