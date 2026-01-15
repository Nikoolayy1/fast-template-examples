<img width="1280" height="720" alt="image" src="https://github.com/user-attachments/assets/d98aeb12-6065-418b-a78f-a67479e4fdc9" />


Use the API endpoint /mgmt/shared/fast/applications to POST this on F5.



<img width="616" height="362" alt="image" src="https://github.com/user-attachments/assets/bc5e64b4-7cac-4e61-8cea-85455b71329a" />


{
   "name": "examples/simple_http",
   "parameters": {
      "tenant_name": "Tenant1",
      "application_name": "Application1",
      "virtual_port": 443,
      "virtual_address": "192.168.1.0",
      "server_port": 80,
      "server_addresses": ["10.10.10.1"]
   }
}


Another way is Visual Studio F5 Extension.

<img width="1408" height="936" alt="image" src="https://github.com/user-attachments/assets/3d2c64ae-ed50-47d1-ae37-4881037d1652" />
