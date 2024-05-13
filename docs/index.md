# BITRA HEMANTH
Site Reliability Engineer at [DBS Tech India](https://www.dbs.com/dbstechindia/index.html)(DBS Bank)

## Work Experience

### [DBS Tech India](https://www.dbs.com/dbstechindia/index.html)
->_Hyderabad, India_

|**eFx Application Site Reliability Engineer**|->_Aug 2021 to Present_|
|---|---|

- Debugging and Supporting front office forex trade tickets issues in production.  
- Deployment activity like deploying microservices in openshift, mariadb database patching, OS patching.
Troubleshooting in OpenShift
- Investigation, troubleshooting & debugging pricing issue, booking issue for vendor Applications ET2 (RET) , and other internal applications trading issues.
- Automation of manual tasks / activity with shellscripting and python scripting in PROD and UAT, 
- Scheduling and Co-ordinating OS, MariaDB, Openshift patching activity for production and UAT.

#### challenges solved  

**Problem Statement**  

For ET2 Forex Application, one of the module called RFQ (Request for Quote) program,  
we perform live verification using __SOAP UI__ and __PostMan__ with XML Rest API,  
but organization discontinued the software for the current project.  
We have to create some tool which can help to perform live verification even through command line or GUI.  

**Solution**  

- Written a python program to execute in commmand line to read XML Rest API  
  call the API and display the output in the command line and sent output to internal email as a verification.  

##### **Certifications**  

![CKA](https://raw.githubusercontent.com/hemanth22/Images/master/cka-certified-kubernetes-administrator.png)  
#### [CKA Certificate link](https://www.credly.com/badges/8d975c03-cb2a-454d-9f72-3d5c63e84561/public_url)

### [Societe Generale Global Solution Centre](https://www.societegenerale.asia/en/country-details/country/india-2/)
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
   - Developed a Python program to modify the sequencing logic within the 10GB file.  
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
