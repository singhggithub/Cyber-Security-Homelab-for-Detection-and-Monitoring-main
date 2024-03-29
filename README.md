# Cyber-Security-Homelab-for-Detection-and-Monitoring

* Homelab:
A Homelab, as the name implies, is an environment in your home that is used to practice and improve your skills in a specific field. This home lab has components and tools similar to large-scale infrastructures. It’s a safe environment to work with these components and learn how they work.

* TECHNOLOGY USED:
1. VM Ware
2. Kali Linux
3. pfSense Firewall
4. Splunk(SIEM)
5. Security Onion IDS
6. Windows Server 2016 (Active Directory)

* IMPLEMENTATION DETAILS:
  1. Downloading & Installing VMware Workstation Pro
  2. Configuring pfsense
  3. Configuring Security Onion
  4. Configuring Kali Linux
  5. pfsense Interfaces and Rules
  6. Configuring Windows Server as a Domain Controller
  7. JOINING THE PCs TO THE DOMAIN
  8. Installing Splunk on a Ubuntu Server
  9. Installing Universal Forwarder on Windows Server
      ![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/6b304190-92af-4518-a1b8-5ccc53c915da)
     ![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/0f08529d-563e-416c-8da6-f91eae0ca59b)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/f56a59cc-9353-4885-b0bc-7dd29bc16c3c)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/c995d084-85b0-427e-bda4-40668630260d)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/e560ca2a-bb60-4d7c-ae50-01214d49d209)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/f079a6a4-305e-423b-88fe-a0b9794fc66c)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/c0da8a98-c8f7-447b-8000-cfadc7584350)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/ad547055-3a47-44bc-a324-a55fb771f788)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/9da7707f-8a0e-4e07-a3bc-3c5306bea63b)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/52e08417-a9d9-4975-b4c9-231dfe6a05f5)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/4e2ada23-a239-4ac8-a480-4fb2fe351945)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/ab68e8a3-d37a-4212-ad5d-ec197a41bf29)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/78a01296-8206-41a2-a08b-77a84639baac)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/cc1eea96-7595-4268-bebf-0a3003788d7c)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/b5b6b3d7-f867-40bf-88dd-33906dadad59)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/2a49c1a4-b142-4fd1-aea6-a87f9a021c02)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/5db2cd93-0ba8-4802-835f-784583ff5b8d)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/d26302f2-c07d-4cd8-854f-85d963364cee)
![image](https://github.com/prasannasec/Cyber-Security-Homelab-for-Detection-and-Monitoring/assets/63840948/d674a5d4-2f34-4577-8c87-f2d86fdc1c65)

* As we implemented IDS, IPS, Firewall and SIEM tools from various vendors, we can generate, detect, and monitor logs from these Gateway security devices.
* A secure web gateway protects our network from online security threats and infections by enforcing policy and filtering Internet-bound traffic. A secure web gateway is an on-premise or cloud-delivered network security service. Sitting between users and the Internet, secure web gateways provide advanced network protection by inspecting web requests against security policy to ensure malicious applications and websites are blocked and inaccessible. A secure web gateway includes essential security technologies such as URL filtering, application control, data loss prevention, antivirus, and https inspection to provide organizations with strong web security.
* SIEMs collect logs and events from hundreds of organizational systems (for a partial list, see Log Sources below). Each device generates an event every time something happens, and collects the events into a flat log file or database. The SIEM can collect data in four ways:
