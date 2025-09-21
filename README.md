# Splunk-Basics-VPN Log Analyser Dashboard 🎯
**🧠 Summary / What It Does**

This project is a slick dashboard built to analyze VPN event logs using Splunk. It digs into IP activity, user events, and country data, turning raw logs into actionable insights. Whether it’s tracking events by IP (like 107.3.206.58 with 14 events) or spotting user trends (hello, Maleena with 60 logs!), this tool proves you can tame the wild world of data. It’s a testament to my ability to handle real-world log analysis with a forward-thinking edge! 

**⚙️ Tools & Tech**

Splunk Enterprise: The backbone for log indexing and visualisation.

JSON: Data source format for those VPN logs.

Query Skills: Crafting searches like a pro (e.g., filtering out France with 2,814 events).

**🗂️ Features**

This project successfully answers several key questions about the dataset, demonstrating specific analytical capabilities:

**Real-time event counting: Ingested a log file into Splunk and accurately counted the total number of events.**


<img width="1816" height="180" alt="Splunk Basic Questions 1 " src="https://github.com/user-attachments/assets/cb36e882-b2b6-4db9-859c-ab18d10e3745" />

<img width="1891" height="613" alt="splunk basic answer 1 " src="https://github.com/user-attachments/assets/f0e94cda-ab25-45bd-8aac-b0e0b21b5676" />



**User event tracking: Determined the exact number of log events captured for a specific user.**


<img width="1800" height="169" alt="Splunk Basic Questions 2 " src="https://github.com/user-attachments/assets/b85a3ae2-0364-4eb9-9670-79f992bc0c5f" />

<img width="1419" height="673" alt="splunk basic answer 2 " src="https://github.com/user-attachments/assets/73c71fa3-3c61-4f63-9d23-b7b2dd18d897" />


**IP-specific analysis: Wrote queries to identify the specific user associated with a given IP address.**

<img width="1809" height="149" alt="Splunk Basic Questions 3 " src="https://github.com/user-attachments/assets/dba1f1f6-a41b-479e-b9af-3a314b73d510" />

<img width="1901" height="861" alt="splunk basic answer 3 " src="https://github.com/user-attachments/assets/3778b3d3-c1e0-4d7b-a9a2-9876a83896d6" />


**Country-based filtering: Filtered events to identify all log entries originating from countries except a specified one, showcasing the use of NOT operators and geographical fields.**


)<img width="1795" height="179" alt="Splunk Basic Questions 4 " src="https://github.com/user-attachments/assets/6200d44e-b28f-4fc0-aa1a-e137aff91a7f" />

<img width="1896" height="870" alt="splunk basic answer 4 " src="https://github.com/user-attachments/assets/7e9c1067-eaca-4a8b-89cd-c5a9a5292df1" />



**Event Count by IP: Queried and confirmed the number of events observed by a particular IP address.**

<img width="1803" height="167" alt="Splunk Basic Questions 5 " src="https://github.com/user-attachments/assets/238efd3d-6436-40ce-a73a-1df0e126155e" />

<img width="1895" height="890" alt="splunk basic answer 5 " src="https://github.com/user-attachments/assets/2d6b9ccb-3f68-4370-996f-df128353b6df" />




**✅ What I Learned**


Mastering Splunk queries to filter and index massive datasets.

Turning raw data into clear, visual stories (those timelines don’t lie!).

The art of spotting patterns, like why Maleena’s logs stand out.

Patience with log files, 2,862 events don’t analyse themselves! 

**📚 Resources**

Splunk Documentation (the old-school way to learn the ropes).

Stack Overflow (for those tricky query tweaks).

My own grit, because sometimes you just figure it out!

**🙌 Credits / Acknowledgements**

Big thanks to the Splunk community for the tips, and to myself for grinding through those logs. Also, a nod to the data gods for keeping it interesting! 🙏
