# Predix 101

---

# What is Predix?

Predix is software optimized for building and running industrial internet applications.

Predix is a Platform-as-a-Service (PaaS) that helps companies:

* Capture and analyze large amounts of industrial data
* Create a system-wide view of assets
* Quickly develop and deploy industrial apps
* Leverate and ecosystem of services built and maintained be GE and partners

---

# What types of applications run on Predix?

* Monitoring of industrial equipment
* Predictive analysis
* Economic optimizations of assets
* Process automation

---

# Application qualities

* Ingest machine and sensor generated data
* Provide insights using analytics
* Manage information access
* \* Not intended for real-time (sub-second) systems
* Use a microservices architecture
* Follow guidelines for [12 Factor App](https://12factor.net/)

---

# Predix Primary Components

* Predix Machine
* Predix Cloud
* Predix Services

---

![Components](assets/PredixComponents.png)

---

# Predix Machine

* Device-independent software used to gather data and push it to the cloud
* Installed on gateways, industrial controllers, and sensors
* Responsible for communicating with the industrial asset and Predix cloud
* Can run local applications, such as edge analytics
* Uses OSGi framework


---

