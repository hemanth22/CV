# BITRA HEMANTH
Site Reliability Engineer at [DBS Tech India](https://www.dbs.com/dbstechindia/index.html)(DBS Bank)

## Work Experience

### [DBS Tech India](https://www.dbs.com/dbstechindia/index.html)
->_Hyderabad, India_

|**eFx Application Specialist Developer**|->_Aug 2021 to Present_|
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
  call the API and display the output in the command line.  

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

**Problem Statement**  

We have production where it generate around 10GB of file, which contains financial data,  
but there is a sequencing logic for inside file which was failing to manage sequencing inside the file.  
So it is difficult to open the file change sequence manually.  


**Solution**  

- To solve this issue, i have written a python program to change the sequencing logic in the 10GB file and save it.  
- As per project requirement, i have learnt dotnet and re-written the logic in dotnet program and implemented in production.  


**Problem Statement**  

Once there was a production issue, there was huge difference between number of lines and filesize of data from previous and current month.  
Upstreams application don't have any option to check on the difference of the file.  
We have to check manually as per the Finance team request, or else it will impacting Monthly regulatory reporting.  

**Solution**  

- I have created a python program that will compare the data between last working day of the last month data and last working of the current month data folders
- sends difference of data through mail to upstream to confirm, if data quality difference is fine
- if fine, we will integrate upstream data, or else upstream will verify the data again.

**Problem Statement**  

On daily basis, we send multiple files to file transfer system (i.e. UI created with IBM SFG),  
through this portal, we can see number of files are sent and timing details,  
but it display 10 records only at once, but we want to check 150 files at once.  

**Solution**  

- I have created a python program to create a daily end of the day report, to connect to file transfer system
- get the data from file transfer system, but response will be in json format
- we parse the json data into table format in regional wise and final mail is sent to our team.

**Problem Statement**  

We have few critical jobs in production, we need to check manually in autosys UI,  
due to some code issue, job doesn't fail properly and it will be in running state in autosys UI,  
even the fix is applied behavior job is still same, but it need to be verified on daily basis.  

**Solution**  

- For this issue, i have written a lucence query, that will fetch the jobs status from elasticsearch 
- creates a report in mail and sends mail specific intervals of time and end of day report.

**Problem Statement**  

We get files from upstream which contains critical data for processing of daily end of month report for india regulatory reporting.  
But sometime upstreams sent zero data files and half processed files which was creating accounting reconciliation breaks for end of month.  

**Solution**  

- First we took average file size which we recieve from upstream every month.
- Using autosys, we have create a filewatcher to monitor zero data and  
  partial data file size and fail it to prevent data integration and get an alert to the team  

##### **Certifications**
![DevOps](https://raw.githubusercontent.com/hemanth22/Images/master/devops_image.png)
#### [DevOps Certificate link](https://raw.githubusercontent.com/hemanth22/Images/master/DevOpsCertificate.jpg)


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
