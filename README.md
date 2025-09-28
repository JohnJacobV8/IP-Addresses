# IP Addresses – The Digital ID of Devices  

In my certification in **Fundamentals of Programming and Software Engineering at Platzi**, we studied how IP addresses work, one of the essential foundations of every digital network.  

IP addresses are like the **ID card** of each connected device. Just as your house has a physical address (street, number, postal code), every computer, phone, or smart TV connected to the Internet needs a unique address to be found.  

---

## IPv4 – The Classic Model  
In its most classic form, IPv4, these addresses are written as four groups of numbers separated by dots, like: 128.100.20.5

Each group can have a value from 0 to 255 because each one represents a byte of information (8 bits).  
- An IPv4 address uses **32 bits in total**.  
- This allows about **4.3 billion unique combinations**.  

When DARPA designed this architecture in the early days of the Internet, they never imagined that millions of servers, smartphones, IoT devices, and even household appliances would each need their own address.  

---

## IPv6 – The Infinite Expansion  
As the Internet grew, it became clear that IPv4 addresses would run out. That’s why, in 2017, the IPv6 standard was consolidated:  
- Uses **128 bits instead of 32**.  
- Written in **8 groups of 4 hexadecimal digits**.  
- Example: 2001:0db8:85a3:0000:0000:8a2e:0370:7334
- Groups of zeros can be compressed: 2001:0db8:85a3::8a2e:0370:7334


With IPv6, the number of addresses is so astronomically high that we could assign several to every atom on the surface of the Earth.  

---

## Public vs. Private Addresses  
- **Public IPs**: Unique and visible across the Internet (assigned by your ISP).  
- **Private IPs**: Used inside local networks (like your home WiFi). They can repeat across different homes without conflict.  

To allow private devices to communicate with the Internet, routers use **NAT (Network Address Translation)**, which:  
- Translates private IPs into the public IP of your Internet connection.  
- Tracks which internal device made each request.  
- Routes responses back to the correct device.  

Without NAT, IPv4 would have collapsed long ago.  

---

## Localhost – 127.0.0.1  
There is a special IP address every programmer should know: 127.0.0.1 

Also called **localhost**, it always points to your own machine. It is essential for developing and testing applications locally without needing external connectivity.  

---

## Why does it matter?  
Even though today we use domain names like `google.com`, beneath that friendly layer, **everything still works with numbers**.  

Understanding IP addresses helps with:  
- 🔹 Debugging network issues.  
- 🔹 Configuring servers correctly.  
- 🔹 Implementing security rules.  
- 🔹 Optimizing distributed applications.  

---

## Conclusion  
IP addresses give **order and direction** to our global connectivity. They are the **map** that makes it possible for a message to travel from your computer to any corner of the planet in milliseconds.  

---

✍️ John López  
👉 GitHub: [https://github.com/JohnJacobV8](https://github.com/JohnJacobV8)  
👉 Connect with me on LinkedIn: [https://www.linkedin.com/in/johnjacobv8](https://www.linkedin.com/in/johnjacobv8)  

<img width="1536" height="1024" alt="IP-ADRESSES" src="https://github.com/user-attachments/assets/dfe0b79b-da65-4f38-a4ca-17370141e15d" />
