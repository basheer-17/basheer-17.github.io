<h1 align="center"> CEH Day 5 – Footprinting & Reconnaissance </h1>

Footprinting and Reconnaissance is the **first phase of ethical hacking**. It involves gathering information about a target system, network, or organization to understand its security posture and identify potential attack surfaces.

---

## Objectives of Footprinting & Reconnaissance
- Understand the target environment
- Identify potential vulnerabilities
- Collect information legally and ethically
- Reduce risks in later attack phases
- Build a detailed profile of the target

---

## What is Footprinting?
Footprinting is the process of collecting **basic and detailed information** about a target system, network, or organization. It helps attackers and ethical hackers understand how the target operates.

## What is Reconnaissance?
Reconnaissance is the continuation of footprinting where collected information is analyzed and verified. It may involve interaction with the target system to gather more accurate data.

<center>
  <img src="images/107.png" alt="Image2">
</center>

---

## Types of Footprinting & Reconnaissance
- Footprinting is classified into the following two types:

<center>
  <img src="images/108.jpg" alt="Image2">
</center>

### 1. Passive Footprinting
- No direct interaction with the target.
- Uses publicly available information.
- Low risk of detection.
**Example**:
- Reviewing the organization's official website.

### 2. Active Footprinting
- Direct interaction with target systems.
- Uses probing and scanning techniques.
- Higher risk of detection.

---

## Footprinting Methodologies

### 1. Footprinting Through Search Engines
- Uses search engines to gather publicly available data.
- Helps find exposed files, directories, and sensitive information.
- Identifies misconfigured systems and leaked credentials.

### 2. Footprinting Through Web Services
- Uses online tools and web-based services.
- Collects information such as domain details, IP addresses, and DNS records.
- Helps map the target’s online infrastructure.

### 3. Footprinting Through Social Networking Sites
- Gathers information from platforms like LinkedIn, Twitter, and Facebook.
- Collects employee roles, job titles, locations, and technologies used.
- Helps understand organizational structure.

### 4. Website Footprinting
- Analyzes the target’s website.
- Identifies server type, technologies, frameworks, and directories.
- Helps detect outdated software and misconfigurations.

### 5. Email Footprinting
- Collects email addresses and email formats.
- Identifies mail servers and security mechanisms.
- Useful for understanding communication patterns.

### 6. WHOIS Footprinting
- Collects domain registration information.
- Identifies domain owner, registrar, and contact details.
- Helps map organizational assets.

---

## Information Obtained During Footprinting

### 1. Network Information
- Domain names
- IP addresses
- Network ranges
- DNS records
- Network topology

### 2. System Information
- Operating systems
- Server types
- Software versions
- Web technologies
- Security mechanisms

### 3. Organization Information
- Company name and structure
- Employee details and roles
- Physical locations
- Business operations
- Publicly available security policies

---

### Ping Command
- Open the terminal and run the command:
- ping <website_name>
- This command checks whether the target website is reachable and displays its IP address along with response time.
<center>
  <img src="images/109.png" alt="Image2">
</center>

---

### Access Website Using IP Address
- Open the web browser (firefox) in Parrot OS and enter:
- ip://<IP_Address>
- This is used to check whether the website responds directly through its IP address instead of a domain name.
<center>
  <img src="images/110.jpg" alt="Image2">
</center>

<center>
  <img src="images/111.png" alt="Image2">
</center>

---

### Searching for Bing in Firefox
- Open Firefox browser and search for “Bing”.  
- Open the Bing search engine and enter the target website name or IP address in the search bar to gather publicly available information.

---

### Installing and Using Wappalyzer
- Open Firefox and go to the browser add-ons store.  
- Install the Wappalyzer extension.  
- Visit the target website and click on the Wappalyzer icon to view the technologies used by the website.
<center>
  <img src="images/112.png" alt="Image2">
</center>

<center>
  <img src="images/113.png" alt="Image2">
</center>

<center>
  <img src="images/114.png" alt="Image2">
</center>

---

### Running WHOIS Command in Terminal
- Open the terminal and run the command:
- whois <website_name>
- This command displays domain registration details such as registrar, creation date, and ownership information.
<center>
  <img src="images/115.png" alt="Image2">
</center>

---

### WHOIS Lookup Using Browser
- Open a web browser and visit a WHOIS lookup website.  
- Enter the target domain name and submit the query to view domain registration details.
<center>
  <img src="images/116.png" alt="Image2">
</center>

---

### Fake Name Generator
- Open a fake name generator website.  
- Generate random identity details such as name, address, and contact information for testing purposes.
<center>
  <img src="images/117.png" alt="Image2">
</center>

<center>
  <img src="images/118.png" alt="Image2">
</center>

---

### Fake Profile Image Generation
- Open the website “This Person Does Not Exist”.  
- Refresh the page to generate AI-based human face images that do not belong to real individuals.
<center>
  <img src="images/119.png" alt="Image2">
</center>

---

### Grabify
- Open the Grabify website and generate a tracking link.  
- When the link is accessed, IP address and basic device information are logged.
<center>
  <img src="images/120.png" alt="Image2">
</center>

---

### IP Lookup
- Retrieves geographical and network details of an IP address
- Open an IP lookup website.  
- Enter the target IP address to view location, ISP, and network-related details.
- It provides:
  - Country
  - Region
  - ISP
  - Organization information

---

### I Know What You Download
- Displays publicly visible torrent activity linked to an IP address.
- It shows: 
  - File names
  - Download timestamps
  - Torrent hashes
- Uses public BitTorrent Tracking data and does not directly identify individuals.
<center>
  <img src="images/121.png" alt="Image2">
</center>

---

### Installing Hound in Parrot OS
- Search for hound github in the browser
<center>
  <img src="images/122.png" alt="Image2">
</center>

- Open the terminal in Parrot OS and clone the Hound Repository.
  - git clone https://github.com/techchipnet/hound.git
- This command downloads the Hound OSINT tool into the system for footprinting purposes.
- Navigate to the hound Directory by running the command:
  - cd hound
- Give execute permission:
  - chmod +x hound.sh
- Run the Hound tool
  - ./hound.sh

<center>
  <img src="images/123.png" alt="Image2">
</center>

<center>
  <img src="images/124.png" alt="Image2">
</center>
