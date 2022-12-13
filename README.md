# Cyber Resiliency Solutions with IBM QRadar

This repository contains links to solution blueprints, video demos and Python code published for all the cyber resiliency solutions for various IBM Storage Products and third party vendor products

## Following solutions are currently published. Keep watching this space for new additions.

##
- ### IBM Spectrum CDM + FlashSystem Safeguarded copy for SQL database
- ### IBM DS8000 Safeguarded Copy
- ### Brocade SAN FOS

##

# IBM Spectrum CDM + FlashSystem Safeguarded copy for SQL database
The focus of this solution is to highlight early threat detection by IBM® QRadar® and to proactively start a cyber resilience workflow in response to a malicious uer actions.

The workflow uses IBM Spectrum Copy Data Management (SCDM) as orchestration software and initiates restore from last Safeguarded Copy backup to a clean environment.

The resources published for this solution are as following.

| Type  | Reference |Comment|
|-------|-----------|-------|
|GitHub Repository|[ibm-qradar-cdm-fs-safeguarded-copy](https://github.com/IBM/ibm-qradar-cdm-fs-safeguarded-copy)|Use the link to visit the GitHub repository containing Python code|
|Document|[Blueprint](https://www.redbooks.ibm.com/abstracts/redp5691.html)|Solution blueprint|


# IBM DS8000 Safeguarded Copy

The focus of this solution is to highlight early threat detection by IBM® QRadar® and to proactively start a cyber resilience workflow in response to a cyberattack or malicious user actions.

The workflow uses IBM Copy Services Manager (CSM) as orchestration software to start IBM DS8000® Safeguarded Copy functions. The Safeguarded Copy creates an immutable copy of the data in an air-gapped form on the same DS8000 system for isolation and eventual quick recovery.

The resources published for this solution are provided below.

| Type  | Reference |Comment|
|-------|-----------|-------|
|GitHub Repository| [ibm-qradar-ds8k-sgc-csm](https://github.com/IBM/ibm-qradar-ds8k-sgc-csm) |Use the link to visit the GitHub repository containing Python code written to invoke Copy Services Manager pre-configured scheduled task to invoke SafeguardedCopy on DS8000 |
|Document|[Blueprint](https://www.redbooks.ibm.com/abstracts/redp5677.html?Open)|Solution blueprint|
|Video|[Video demo](https://mediacenter.ibm.com/media/Early+Threat+Detection+and+Cyber+Resiliency+on+the+IBM+DS8000%2C+with+QRadar%2C+Copy+Services+Manager%2C+and+Safeguarded+Copy/1_mp17k1at)|Video demo of the solution|


# Brocade SAN FOS 

Enterprise networks are large and rely on numerous connected endpoints to ensure smooth operational efficiency. However, they also present a challenge from a security perspective. 

The focus this solution is to demonstrate an early threat detection using IBM QRadar, against network fabcic powered by Brocade SAN FOS.

The resources published for this solution are provided below.

| Type  | Reference |Comment|
|-------|-----------|-------|
|GitHub Repository| [ibm-qradar-brocade](https://github.com/IBM/ibm-qradar-brocade) |Use the link to visit the GitHub repository containing Python code written to bridge the gap between IBM QRadar and Brocade SAN FOS.|
|Document|[Blueprint](http://www.redbooks.ibm.com/abstracts/redp5672.html?Open)|Solution blueprint|
|Video|[Video demo](https://mediacenter.ibm.com/media/Overview+and+Deep+Demo+of+how+to+quickly+setup+Cyber+Resilience+using+IBM%27s+QRadar+and+Brocade+SAN+components/1_3gnrcu5r)|Video demo of the solution|
