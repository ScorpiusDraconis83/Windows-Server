### **Explaining in Story Form: Nikhil and His Secondary DNS Server**

#### **Story Title: "Nikhil and His Backup Friend"**

**Characters:**

* **Nikhil**: A regular internet user
* **Backup Friend**: Nikhil's secondary DNS server, always ready to help

---

#### **The Story Begins:**

Once upon a time, there was a boy named Nikhil who loved browsing websites on the internet. He had a main computer that he used for all his tasks. However, Nikhil knew that sometimes his computer might stop working or shut down.

**Nikhil thought, "If my computer doesn't work, how will I access websites?"**

#### **The Role of the Backup Friend:**

To solve this problem, Nikhil set up a Backup Friend (Secondary DNS Server). This friend was always ready, so if Nikhil's main computer didn't work, the Backup Friend could step in and help.

1. **Making a Copy of the Information**:

   * The Backup Friend made a copy of all the websites' names and their corresponding numbers (IP addresses) from Nikhil's main computer.
   * Whenever Nikhil added a new website name on his main computer, this Backup Friend would also keep a copy.

2. **Ready to Help at Any Time**:

   * When Nikhil typed "example.com" and his main computer didn't work, the Backup Friend immediately said, "Don't worry, I can help! The IP address is 93.184.216.34."
   * Nikhil said, "Wow! You are such a good friend!"

#### **The Problem Solved:**

One day, Nikhil's main computer suddenly shut down. He was very worried because he needed to visit an important website. But quickly, he turned to his Backup Friend.

* He asked his Backup Friend, "I need the IP address for 'example.com'."
* The Backup Friend immediately responded, "The IP address is 93.184.216.34."

Nikhil connected to that IP address and accessed the website without any issues.

#### **Conclusion:**

In this way, Nikhil and his Backup Friend worked together to help Nikhil access websites.

**This is exactly how a Secondary DNS Server works.** It's like a backup that helps the Primary DNS Server. If the Primary DNS Server isn't working, the Secondary DNS Server steps in immediately and converts the website names to their respective IP addresses.

---

### **What is a Secondary DNS Server?**

A **Secondary DNS Server** is a type of DNS server that holds a copy of the information from the Primary DNS Server. Its primary job is to assist in answering DNS queries if the Primary DNS Server is unavailable.

### **How Does a Secondary DNS Server Work?**

1. **Making a Copy of the Information**:

   * The Secondary DNS Server holds a copy of all DNS records from the Primary DNS Server. This information is regularly copied from the Primary to the Secondary DNS Server via a process called **"zone transfer"**.
2. **Answering Queries**:

   * When a user types a website name, a DNS query is sent for that name. If the Primary DNS Server is not available, the Secondary DNS Server responds with the IP address.

### **Why Use a Secondary DNS Server?**

1. **Reliability**:

   * A Secondary DNS Server acts as a backup. If the Primary DNS Server fails, the Secondary DNS Server immediately steps in to assist. This ensures that websites are always available.

2. **Load Balancing**:

   * With multiple DNS servers, it's easier to balance the load for users. This improves website loading speeds.

3. **Protection**:

   * If the Primary DNS Server faces any issues, such as a DDoS attack, the Secondary DNS Server immediately takes over to maintain service.

### **Example**

Let’s say you have a website called "mywebsite.com":

* Your Primary DNS Server holds all the DNS records for this website.
* If for any reason, the Primary DNS Server is down, the DNS query for "mywebsite.com" is sent to the Secondary DNS Server.
* The Secondary DNS Server converts the name to its IP address (for example, 192.0.2.1) and sends it back to the user.

In this way, users can access the website without any disruption.

### **Conclusion**

A **Secondary DNS Server** is an essential tool that ensures the availability and reliability of websites. It works alongside the Primary DNS Server to make sure users always get the correct information, whether the Primary Server is available or not.

---
![Primary and Secondary Server with Zone](https://github.com/nikhilpatidar01/Windows-Server/raw/Master/DNS-Domain-Name-System/Diagram%20Photo/Primary%20and%20Secondory%20Server%20with%20Zone.png)

---
