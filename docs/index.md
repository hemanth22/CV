# BITRA HEMANTH
Site Reliability Engineer at [DBS Tech India](https://www.dbs.com/dbstechindia/index.html)(DBS Bank)

## Work Experience

### [Standard Chartered Global Business Services](https://www.sc.com/in/business-global-banking/)
->_Bangalore, India_

|**Support Specialist**|->_March 2025 to Present_|
|---|---|

- I focused on enhancing system reliability and efficiency in high-frequency trading environments.  
- Investigated and resolved critical pricing and booking issues for the S2BX Application and FIX Sessions.  
- Handled incidents and change requests to maintain operational integrity in a high-frequency trading environment  
- Leveraged automation with Ansible and Python to minimize manual processes and improve productivity.  


#### challenges solved  

**Problem Statement:**  

__Challenge:__ The Java Web Start–based application frequently crashed or froze due to excessive cache buildup.
__Issue:__ - The desktop application S2BX, running on Java 1.8, often experienced freezing, hanging, or performance degradation caused by large amounts of cached data.  

**Solution:**  

__PowerShell Script Development:__
  - Created a PowerShell script to automatically clean up Java cache on user desktops.
  - Documented script usage and shared guidelines with the team to ensure consistent adoption.

__Results:__  
__Efficient Automation:__  
  - Reduced manual effort by automating cache cleanup.  
  - Improved application stability and responsiveness.  
  - Enhanced user productivity by minimizing downtime.  

### [DBS Tech India](https://www.dbs.com/dbstechindia/index.html)
->_Hyderabad, India_

|**eFx Application Site Reliability Engineer**|->_August 2021 to March 2025_|
|---|---|

- Debugging and Supporting front office forex trade tickets issues in production.
- Writing Jenkins pipeline accordingly to deployment requirement
- Deployment activity like deploying microservices in openshift, mariadb database patching, OS patching.
Troubleshooting in OpenShift
- Investigation, troubleshooting & debugging pricing issue, booking issue for vendor Applications ET2 (RET) , and other internal applications trading issues.
- Automation of manual tasks / real time activity with shellscripting and python scripting in PROD and UAT, 
- Scheduling and Co-ordinating OS, MariaDB, Openshift patching activity for production and UAT.

#### challenges solved  

**Problem Statement:**  

__Challenge:__ The application reached the decommission stage, but the Dev team was already out of budget for further regression testing.  
__Issue:__ Despite the application being decommissioned, six tier-1 App Services still needed to run until they were migrated to a different application. To maintain server security and vulnerability-free status, we had to upgrade from RHEL Version 7.9 to RHEL Version 8.8. However, the Dev team lacked the budget for extensive regression testing.  
**Solution:**  

1. __Custom Python Program for Automated Regression:__
   - Developed a Python program to execute from the command line.
   - __XML Rest API Interaction:__
     - Read data from an XML Rest API designed for 40 test cases.
     - Called the API endpoints for all 40 test cases.
     - Captured the API responses for each test case.
   - __Automated Email Verification:__
     - Collated the API responses on the server.
     - Sent consolidated responses via email.
     - Printed the API responses in a table format, organized by test case.

__Results:__  
__Efficient Automation:__ Automated regression testing reduced manual effort significantly—from 5 days to just 1 day.  
__Accelerated Sign-off Process:__ Faster regression testing facilitated timely sign-off for server RHEL upgrade and patching.  

**Problem Statement:**  

__Challenge:__ The organization-wide migration of OpenShift from Cluster A to Cluster B required efficient handling of 1000+ DeploymentConfigs and 3000+ Pods across 14 different projects.  

__Issue:__ Manual shutdown and subsequent manual scaling of services in Cluster B was time-consuming and complex.  

**Solution:**  

__Automated Backup and Scaling Script:__  
- Developed a set of __shell scripts__ to automate the migration process.  
- __Backup of Pods:__  
  - Created a script to take an __exact backup__ of the pod count for each DeploymentConfig using OpenShift command-line tools and `awk`.  
  - Ensured accurate data preservation during the migration.  
 - __Scaling Down and Up:__
   - Wrote scripts to __scale down__ pods under DeploymentConfigs in Cluster A.
   - After migration, scaled up the pods in Cluster B based on the previous backup.
   - Reduced manual effort and ensured consistency.

__Results:__

__Efficient Automation:__ The script significantly reduced manual work, especially for scaling down services from the OpenShift UI.  
__Streamlined Migration:__ Faster and more reliable migration process with minimal human intervention.  

**Problem Statement:**  

__Challenge:__ The organization discontinued the use of SOAP UI and PostMan for live verification of the RFQ (Request for Quote) program.  

__Issue:__ The absence of suitable tools hindered the ability to perform live verification efficiently.  

**Solution:**  

1. __Custom Python Program for Live Verification:__  
   - Developed a __Python program__ to execute from the command line.  
   - __XML Rest API Interaction:__  
     - Read data from the XML Rest API.  
     - Called the API endpoints relevant to the RFQ module.  
     - Captured the API response.  
   - __Command Line Output:__  
     - Displayed the API response in the command line interface.  
     - Enabled real-time verification of RFQ data.  
   - __Automated Email Verification:__  
     - Sent the API response output to an internal email address for live verification.  

__Results:__  

__Efficient Live Verification:__ The custom Python program streamlined the RFQ verification process.  
__Proactive Communication:__ Immediate email notifications facilitated timely confirmation by the team.  

##### **Certifications**  

![CKA](https://raw.githubusercontent.com/hemanth22/Images/master/cka-certified-kubernetes-administrator.png)  
#### [CKA Certificate link](https://www.credly.com/badges/8d975c03-cb2a-454d-9f72-3d5c63e84561/public_url)

### [Societe Generale Global Solution Centre](https://wholesale.banking.societegenerale.com/en/about/locations/worldwide-details/office/bangalore-global-solution-centre-1/)
->_Bangalore, India_

|**Specialist Software Engineer - DevOps**|->_April 2021 to August 2021_|
|---|---|

- Expertise on X-ONE Trading Suite Application on multiple asset classes: IRD, CDV, Equity, Forex.
- Expertise on Trade Life Cycle


|**Specialist Support Enginer**|->_April 2019 to March 2021_|
|---|---|

- Managing X-ONE Application escalations.
- Supporting Legacy to X-ONE migration.
- Supporting X-ONE Application Transversal topics like IRD, CDV, Forex, Equity, FixedIncome.
- Automating monitoring with elasticsearch and kibana.
- Automating daily/morning check and manual tasks.

#### challenges solved  

**Problem Statement:**  

__Challenge:__ In production, a 10GB file containing financial data had an intricate sequencing logic.  
__Issue:__ The existing sequencing logic was failing to manage the order of data within the file, making manual inspection and sequence adjustments difficult.  

**Solution:**  

1. Python Program for Sequencing Logic:  
   - Developed a __Python program__ to modify the sequencing logic within the 10GB file.  
   - Analyzed the existing logic and identified areas for improvement.  
   - Implemented changes to ensure proper data order and sequencing.  
   - Saved the modified file with the corrected sequencing.  
2. Transition to .NET (Dotnet):  
   - __Learned .NET (Dotnet)__ as per project requirements.  
   - Re-implemented the sequencing logic in a __Dotnet program__.  
   - Ensured compatibility with the existing production environment.  
   - Successfully Executed logic to correct file.  

__Results:__  

__Seamless Data Processing:__ The new sequencing logic resolved issues related to data order and improved file integrity.  
__Reduced Manual Effort:__ Automation eliminated the need for manual sequence adjustments, enhancing efficiency.  

**Problem Statement:**  

__Challenge:__ In production, there was a significant difference between the number of lines and file size of data from the previous month compared to the current month.  
__Issue:__ The upstream application lacked an option to verify these data differences, leading to manual checks upon Finance team requests. Failure to address this issue could impact monthly financial regulatory reporting.  

**Solution:**  

1. __Automated Data Comparison:__  

  - Developed a __Python program__ to compare data between:
    - __Last working day of the last month’s data folder__  
    - __Last working day of the current month’s data folder__  
  - __Data Quality Verification:__  
    - Calculated the difference in data (e.g., line count, file size) between the two time periods.  
    - Sent the data difference report via email to the upstream team for confirmation.  
    - If the data quality difference was acceptable:  
      - Integrated the upstream data into the system.  
    - If not:  
      - Upstream verified the data again before integration.

__Results:__  

__Automated Validation:__ The Python program streamlined data comparison, reducing manual effort.  
__Proactive Communication:__ Immediate email alerts ensured timely resolution based on data quality confirmation.  


**Problem Statement:**  

__Challenge:__ Daily file transfers to the file transfer system (IBM SFG) required manual verification.  
__Issue:__ The UI displayed only 10 records at once, making it cumbersome to check 150 files simultaneously.  

**Solution:**  

1. __Automated Data Retrieval:__  
- Developed a __Python program__ to connect to the file transfer system.  
- Retrieved data from the system, which was returned in __JSON format__.  
- __Efficient Parsing:__
  - Parsed the JSON data into a __tabular format__ organized by region.  
  - Extracted relevant details such as file names, timestamps, and status.  
  - Created a comprehensive report for further analysis.  
2. __Automated Reporting:__  
- Generated a __daily end-of-day report__ summarizing all file transfers.  
- Segregated files by region and displayed their status (successful, partial, or failed).  
- Sent the final report via email to the team.  

__Results:__  
- __Enhanced Visibility:__ The automated report allowed us to monitor 150 files at once, improving efficiency.  
- __Proactive Alerts:__ Immediate email notifications enabled timely action based on file transfer statuses.  

**Problem Statement**  

__Challenge:__ Critical Autosys jobs in production were not failing properly due to code issues.  
__Issue:__ Jobs remained in a running state in the Autosys UI even after applying fixes, leading to manual verification requirements.  

**Solution**  

1. __Lucene Query for Elasticsearch:__  

- Developed a Lucene query to fetch job statuses from Elasticsearch.
- Leveraged data pushed by the application team into Elasticsearch.

- __Automated Reporting:__  

  - Created a report summarizing job statuses.  
  - Sent scheduled email reports at specific intervals and an end-of-day report.  

__Results:__
- __Automated Verification:__ The Lucene query ensured timely status checks without manual intervention.  
- __Proactive Alerts:__ Immediate email alerts enabled prompt action based on job status changes.  

**Problem Statement**  

__Challenge:__ We receive critical data files from upstream for daily end-of-month reports related to India’s regulatory reporting.  
__Issue:__ Sometimes, the upstream sent zero data files or half-processed files, leading to accounting reconciliation breaks at the end of the month.

**Solution**  

__1. File Size Analysis:__  

   - Calculated the average file size received from upstream every month.
   - Considered 75% of the average file size as a threshold.

__2. Implementation Using Autosys:__  

   - Created a __file watcher__ using Autosys.
   - Monitored incoming files for two conditions:
     - __Zero Data Files:__ Detected when the file size was zero.
     - __Partial Data Files:__ Detected when the file size was less than 75% of the average size
   - __Action Taken:__
     - Failed the integration process for such files to prevent reconciliation issues.
     - Generated an __alert__ to notify the team immediately.

__Results:__  
- __Improved Data Integrity:__ By preventing the integration of incomplete or zero data files, we significantly reduced reconciliation breaks.  
- __Enhanced Efficiency:__ The automated filewatcher ensured timely detection and proactive handling of problematic files.  

  ```jil
  insert_job: fw_job
  job_type: FW
  watch_file: /tmp/watch_file.log
  watch_file_min_size: 15728640
  watch_interval: 60
  ```

#### Certifications
![DevOps](https://rawcdn.githack.com/hemanth22/Images/4b62571eba1a330d418cc34fc444875348cb880b/DevOpsCertificate.jpg)  
#### [DevOps Certificate link](https://rawcdn.githack.com/hemanth22/Images/4b62571eba1a330d418cc34fc444875348cb880b/DevOpsCertificate.jpg)


|**Support Engineer**|->_August 2016 to April 2019_|
|---|---|

- X-One is a Trading Application suite.
- Deals are also booked from different external platforms such as markitwire are captured and pushed to X-ONE from FO to BO activity.
- Fixing issues on Paper confirmation and Electronic confirmation like DTCC activity in X-ONE application for IRD and CDV.
- Good understanding on FPML.
- CLS reconiliation for settlement in creder and CDS Roll out.
- Understanding on accounting schema as per IFRS and IAS standards in X-ONE IRD and CDV accounting process.
- Fixing Accounting and Inventory breaks, Settlement and accounting breaks, Market Economic valuation and accounting valuation breaks.

## Skills

Technical: `Python` `Unix` `SQL` `shell scripting` `Kubernetes` `podman` `git` `jenkins` `ansible`

Management: `Kanban Methodology` `Scrum`

## Education

### Jawaharlal Nehru Technological University Hyderabad
->_Hyderabad, India_


|**Bachelor of Technology on Electronic and Communication Engineering**|->_2011-2015_|
|---|---|


## Personal Details

**Date of Birth:** 22nd June 1993


| Email: **<hemanthbitra@live.com>** | Phone: **+91 733 075 6164** | Website: **[bitroid.in](bitroid.in)** |
|---|---|---|


## About my blogs

<table>
  <tr>
    <td align="center"><a href="https://hemanth22hemublogs.blogspot.com/"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/blogger.svg" width="100px;" alt=""/><br /><sub><b>Google Blogspot</b></sub></a>  </td>
    <td align="center"><a href="https://hemanth22hemu.wordpress.com/"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/wordpress.svg" width="100px;" alt=""/><br /><sub><b>Wordpress</b></sub></a>  </td>
      <td align="center"><a href="https://dev.to/hemanth22"><img src="https://d2fltix0v2e0sb.cloudfront.net/dev-badge.svg" width="100px;" alt=""/><br /><sub><b>DEV.To</b></sub></a>  </td>
  </tr>
  
  <tr>
    <td align="center"><a href="https://hemanthbitra.medium.com/"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.13.0/icons/medium.svg" width="100px;" alt=""/><br /><sub><b>Medium</b></sub></a>  </td>
  </tr>
</table> 


## About my magazine writings

<table>
  <tr>
    <td align="center"><a href="https://www.opensourceforu.com/"><img src="https://raw.githubusercontent.com/hemanth22/Images/master/OpenSourceForYou.jpg" width="100px;" alt=""/><br /><sub><b>Open Source for You</b></sub></a>  </td>
  </tr>
</table>

### I have contributed in Tips & Tricks pages in open source for you in below issues.

- OpenSourceforYou - August 2017
- OpenSourceforYou - November 2017
