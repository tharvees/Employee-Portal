![](https://portal.mawarid.com.sa/Employee/UI/assets/images/mawarid-logo-2.png)

# Introduction
   - **_Al Mawarid Manpower_** is a private company . The company currently specializes in the Human Resources area .
   - **Established** in **_2012_**, Al Mawarid Manpower Solutions Company, a closed shareholding company, was one of the first six companies to obtain the recruitment license from the Ministry of Labor and one of the leading companies to work in that field in the Kingdom.
   - Origin : **_Riyadh , Saudi Arabia ._**
# EMPLOYEE PORTAL


# Login URL for Employee portal 
URL : https://portal.mawarid.com.sa/Employee/UI/#/Employee/login

# **_Employee Portal Login Page_**
## **API :**
https://portal.mawarid.com.sa/Employee/api/v2/crm/GetEmployeeByID?IqamaNO

 ![](./Employee%20portal%20imgs/Login%20page.PNG)

 - **_Register Mobile Number_**
   - A employee portal employee must register phone number .
   - And **Iqama Number , Passport Number , Phone Number**  details to give .
   - **_Register Api_**  https://portal.mawarid.com.sa/Employee/api/v2/crm/GetEmployeeByID?IqamaNO

   ![](./Employee%20portal%20imgs/register%20mobile%20number.PNG)

 - **_Update Mobile Number_**
   - This is to update the mobile number instantly .
   - its containing for 
     - **_Iqama Number ,_** 
     - **_Passport Number ,_**    
     - **_Old Phone Number ,_** 
     - **_New Phone Number ._**
   - Update Api 
   https://portal.mawarid.com.sa/Employee/api/v2/crm/GetEmployeeByID?IqamaNO


   ![](./Employee%20portal%20imgs/update%20mobile%20number.PNG)

# **OTP Page**
## **API**
https://portal.mawarid.com.sa/Employee/api/v1/entitytype/productivitymenuitems?ispermission
 
![](./Employee%20portal%20imgs/otp.PNG)

## **Employee Portal Welcome Page**
It contains 13 MenuBar in the left side of the user and they are,

![](./Employee%20portal%20imgs/Capture.PNG)

# **My Profile**
 - My Profile which means an employee's profile . It actually contains a full details of the employee such as **Mawarid Employee ID, Name, Profession, Iqama Number, Nationality, Border NO, Project ID, Project Name, Passport Number, Iqama Expiry Date, Passport Expiry Date, Date of Birth, Arrival Date, Status, Contract Start Date, Contract End Date, Bank Account Number, Phone Number** .
  
# **Contact Info**

  - `Contact info` is an abbreviation for **_contact information_** . Contact information typically refers to details that allow individuals or entities to be reached or contacted . 

  - This information is commonly used in various contexts, such as business, personal communication, and professional networking .

  - Contact info 
      - CoOrdinator -  m.almalahi@mawarid.com.sa
      - Supervisor -  m.almalahi@mawarid.com.sa
      - Call center -  customercare@mawarid.com.sa
        - Mobile Number - 920027202

   ![](./Employee%20portal%20imgs/contact%20info.PNG)

# **Balances**
  - In a financial context, `Balances` often refers to the amount of money in an account. For example, the balance of a bank account is the difference between the credits (deposits) and debits (withdrawals) made in the account.
## **API :**

https://bcp.mawarid.com.sa/api/v1/erp/getBalancesOfVisaVacationAndTicket?EmpNum

![](./Employee%20portal%20imgs/balance.PNG)

### History of Loan
    
### Api  

 <!-- https://portal.mawarid.com.sa/api/v1/erp/getEmployeeLoanDetails?_personnelNumber -->
 
https://portal.mawarid.com.sa/Employee/api/v1/entitytype/field?EntityTypeId

  ![](./Employee%20portal%20imgs/history%20of%20loan.PNG)

# **PaySlip**
  -  Pay slip is a document containing a detailed list about the various components of your salary along with specific details of employment.
  - If you need payslip You can **Download** it 
## **API**
https://bcp.mawarid.com.sa/api/v1/erp/getEmployeePaySlipDetails?_employeeId

![](./Employee%20portal%20imgs/payslip.PNG)


# **Letter Download**
 - `Letter download` typically refers to the process of obtaining or retrieving a letter or document from the internet or a digital platform to your local device. 
 - This can include various types of letters, such as formal letters, business letters, reference letters, or any document that is available for download in a digital format.   
## **API**
https://bcp.mawarid.com.sa/api/v2/crm/GetDownLoadLetterTypes

![](./Employee%20portal%20imgs/letter%20download.PNG)

<!-- file:///C:/Users/HOME/Downloads/BR000145520231228.pdf  -->

# **Observation**
 
  - Employee observation refers to the practice of systematically observing and assessing an employee's job performance, behavior, skills, and interactions within the workplace . 
  - This process is often conducted by supervisors, managers, or designated individuals within an organization as a part of performance management and evaluation . 
  

## **API**
https://portal.mawarid.com.sa/Employee/api/v2/crm/GetIncidentList?EmployeeID

![](./Employee%20portal%20imgs/observation.PNG)

# **Create Observation**

## API

https://portal.mawarid.com.sa/Employee/api/v1/entitytype/form?EntityTypeId

![](./Employee%20portal%20imgs/create%20-observation.PNG)
 
## CaseCategoryEn DropDown API

https://portal.mawarid.com.sa/Employee/api/v2/crm/GetIncidentCategory

 ![](./Employee%20portal%20imgs/dropdown%20-%20observation.PNG)

### Add API

https://portal.mawarid.com.sa/Employee/api/v1/entitytype/dynamic/insert?EntityData

># **Employee Request**
- Employee Request is contains of employee's 
    - **_Leave Request_**
    - **_Final Exit Request_**
    - **_Employee Iqama Renewal_**
    - **_Employee contract Renewal_**
    - **_Employee Inquiry_**

## **_Leave Request_** 

 A leave request is a formal communication from an employee to their employer seeking approval to take time off from work. Employees may request leave for various reasons, including personal matters, family obligations, health issues, vacations, or other personal or professional reasons.

## **API**

https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/Employee/GetEmployeeLeaveRequests?employeeId


and, leave request for more procedures for employee's **_Leave Request Number ,	
External Leave ,	
Leave Type ,	
Vacation Start Date ,	
Vacation End Date ,	
Vacation Period ,	
Afford Fees	,
Benefits Payment ,	
Afford TicketIn voice ,	
Ticket Reservation ,	
Payment Type ,	
Travel Place ,	
Visa Time ,	
Visa Period ,	
City Of Leave ,	
City Of Arrival ,	
Home Country Phone ,	
Remarks	,
Request Date ,	
Request Status ,	
VisaNumber ,	
VisaIssue Date ,	
Visa End Date ,	
Flight Number ,	
Flight Ticket TravelDate ,	
Return Date ._**

### Leave Request Number :
   - A `Leave Request Number` typically refers to a **_unique identifier or code_** assigned to a specific leave request within an organization's tracking or management system.
   - This number is used to distinguish and track individual leave requests efficiently. 
   - Employees and employers can use the Leave Request Number as a reference when communicating about a specific leave request .
   - If you are inquiring about a `Leave Request Number`, it's possible that your organization uses such a system, and you may need to refer to this number when discussing or inquiring about your leave request .
   - **_If you're unsure, it's advisable to check with your company's HR department or the system administrator for clarification ._**

### External Leave :   
   - `External Leave` typically refers to a type of leave or time off from work that is granted to an employee for reasons not directly related to their normal work responsibilities .
   - It often involves situations where an employee needs to be away from work for **_personal or external_** reasons .
   - In many jurisdictions, there are provisions for family and medical leave that allow employees to take time off to address family or health-related matters .
   - Employees may request external leave for personal reasons such as **_family events, relocation, or other non-work-related commitments ._**

### Leave Type :
   - `Leave type` refers to the categorization or classification of different types of leaves or time off that employees may take from work .  
   - Here are some common leave types :
      - **_Vacation Leave_**
      - **_Sick Leave_**
      - **_Personal Leave_**

# Final Exit Request 

## **API** 
 https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/Employee/GetEmployeeEOSRequests?employeeId
   - **`Final Exit Request`** typically refers to a formal procedure or process through which an employee informs their employer of their intention to leave the company permanently .
   - It is essentially a formal notification of resignation or departure, indicating that the employee is making their final exit from the organization .
   - **_Final Exit Request_** contains **_Request Number	
Request Date , Request Status , Request Type , Last Working Date , Visa Start Date , Visa Number , Flight Number , Flight Ticket TravelDate_**	and **_End Of Service Amount ._**

# Employee Iqama Renewal
  - the Iqama (residence permit) for expatriate employees is typically issued for a specific duration, usually one year. **_To continue living and working in the country, employees need to go through the Iqama renewal process before their current permit expires ._** 

## **API**
<!-- https://portal.mawarid.com.sa/Employee/api/v1/entitytype/form?EntityTypeId -->
https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/Employee/GetEmployeeIqamaRenewRequests?employeeId

## Iqama Number
  -  `Iqama` typically refers to a residence permit or residency card issued to expatriates living in Saudi Arabia . 
  -  The `Iqama number` is a unique identification number assigned to each individual holding a valid Iqama . 
  - It is used for various **_administrative and identification purposes, including accessing government services, opening bank accounts, and other official transactions ._**


## **Employee Iqama Renewal :**
   - employee iqama renewal it contains **_Request Number , Customer Approval , PeriodIn Months , Labor Approval , Sales Approval , Renewal Source , Status ._**

![](./Employee%20portal%20imgs/employee%20iqama%20renewal.PNG)

# Employee contract Renewal

## **API** 
https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/Employee/GetEmployeeContractRenewalRequests?employeeId

### Employee Contract Renewal :
  - `Employee contract renewal` refers to the process of **_extending or renewing_** the terms and conditions of an employment contract between an employer and an employee . 

  - Employment contracts typically have a specified duration, and when that period is nearing its end, both parties may decide to renew the contract for an additional period .

  - `employee contract renewal`it contains list of **Request Number ,	
Old Basic Salary , New BasicSalary , Status	Note , Bonus Is Paid ,	
Old Contract End Date , Period In Months , Customer Approval , Labor Approval .**

![](./Employee%20portal%20imgs/employee%20contract%20renewal.PNG)

# Employee Inquiry
 - `Employee inquiry` typically refers to the process of **_seeking information or conducting an investigation related to an employee's work, conduct, performance, or any other relevant aspect of their employment ._** 

 - The purpose of an employee inquiry can vary, but it is often conducted by employers, human resources (HR) departments, or management to gather information or address specific concerns .

## **API**
https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/EmployeeInquiry/GetAllInquiries?employeeId

![](./Employee%20portal%20imgs/employee%20inquiry.PNG)

 - Employee Inquiry it contains **_Inquiry Number , Title , Description ,	
Status Name , Created On , Employee Inquiry Details	, Can Add Notes ._**

## Create - Employee Inquiry

## API
 https://portal.mawarid.com.sa/Employee/api/v1/entitytype/form?EntityTypeId

![](./Employee%20portal%20imgs/create-%20employee%20inquiry.PNG)

### Add API
 
https://portal.mawarid.com.sa/Employee/api/v1/entitytype/dynamic/insert?EntityData

# Employee View
 - `employee view` could refer to the user interface or dashboard that employees use to access and interact with HR-related information . 
 - This could include features such as viewing their **_personal details, pay stubs, benefits information, requesting time off, accessing training materials, and more ._**
 - Employee View it contains of 
   - **Notification**
   - **Announcement**
   - **Appointment**
   - **Traffic Fine List**

## Notification 

## API

https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/Notifications/GetNotifications?employeeId

 - A notification is a message or alert that informs someone about a      **_specific event, update,_** or **_piece of information ._**
 
 - A notification in this portal are **_two(2)_** types of Notification :
   - **_English Notification_**
   - **_Arabic Notification_**

![](./Employee%20portal%20imgs/notification.PNG)

### English Notification API

https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/Notifications/GetNotifications?employeeId

### Arabic Notification API

https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/Notifications/GetNotifications?employeeId

## Announcement

## API
https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/Announcements/GetAnnouncements?user-id

 - An employee **announcement** is a formal communication or notification within an organization to inform employees about **_significant events, changes, or news related to the company ._**

 ![](./Employee%20portal%20imgs/announcement.PNG)

## Appointment

## API 
https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/MainOfficeReserReq/GetAllRequests?employeeId

- An `appointment` generally refers to a predetermined arrangement or scheduled meeting between two or more people at a specified time and place .

![](./Employee%20portal%20imgs/appointment.PNG)

 - **_Active Request_** is often used in the context of computing, networking, and web development to refer to a request or transaction that is currently in progress or has been initiated and is awaiting a response .
 
 - **_Previous Request_** generally refers to a request that was made before the current one in a sequence of requests. In various contexts such as web development, networking, or database interactions, it could imply different scenarios .

## Create - Appointment
###  create API 
 
 https://portal.mawarid.com.sa/Employee/api/v1/entitytype/form?EntityTypeId

![](./Employee%20portal%20imgs/create-%20appointment.PNG)


## Traffic Fine List

## API

https://portal.mawarid.com.sa/Employee/api/v2/employeecrm/TrafficFines/GetAllTrafficFines?employeeId

 - A `Traffic Fine List` typically refers to a compilation or record of fines imposed on individuals for violations of traffic laws and regulations . 

 - Traffic fines are penalties imposed by law enforcement authorities for various traffic offenses, such as speeding, running red lights, improper parking, and other violations .


# Medical Insurance

## API

https://portal.mawarid.com.sa/Employee/api/v2/crm/GetMedicalCover

 - `Medical insurance`, also known as **_Health insurance_**, is a type of coverage that provides financial protection and assistance in covering the costs of medical and health-related expenses . 

 - It is a contractual agreement between an individual or a group and an insurance company, where the insurer agrees to cover all or a portion of the insured person's medical expenses in exchange for regular premium payments .

![](./Employee%20portal%20imgs/medical%20insurance.PNG)

 - If any doubt go to the 
 - Customer Care Email : customercare@mawarid.com.sa
 - Customer Care Number : 920027202
# FAQ

## API
 https://portal.mawarid.com.sa/Employee/api/v1/entitytype/dynamic/get/?entityTypeRecId
- `FAQ` stands for `Frequently Asked Questions.`

- It refers to a list of common questions and their corresponding answers that are compiled to provide information on a particular topic . 

- FAQs are often used on **_websites, product documentation, customer support pages, and other platforms to address recurring queries and help users find information quickly ._**

![](./Employee%20portal%20imgs/faq.PNG)


# FAQ - Admin

## API
https://portal.mawarid.com.sa/Employee/api/v1/entitytype/dynamic/get/?entityTypeRecId

- If `FAQ-admin` is used in a specific context or within a certain system, platform, or organization, it could be a custom term created for **administrative functions related to managing and updating Frequently Asked Questions .** 
- For example, it might be a role or a tool within a website or software system that allows administrators to **_edit, add, or organize frequently asked questions on a webpage or application ._**

![](./Employee%20portal%20imgs/entitytype%20faq.PNG)

- ### Create -EntityTypeFAQ 
  - If `Create -EntityTypeFAQ` is used in a specific context, it could be a command or function within a **_software development environment, content management system, or a proprietary system used by a particular organization ._**
  
  ![](./Employee%20portal%20imgs/create-entity%20type%20FAQ.PNG)

### Add API 
  
https://portal.mawarid.com.sa/Employee/api/v1/entitytype/dynamic/insert?EntityData

  - Add EntityType FAQ is add the employee details for **_ModuleID , Language , OrderID , Question , Answer ._**

### Language Dropdown API

https://portal.mawarid.com.sa/Employee/api/v1/lookupvalues/GetAllByLookTypeId/1
 
 ![](./Employee%20portal%20imgs/language%20dropdown.PNG)

  - Entity type FAQ employee details for insert and update the details information . 

### Edit popup API

https://portal.mawarid.com.sa/Employee/api/v1/entitytype/form/activationrecorddetails/68

### Update API
    
  https://portal.mawarid.com.sa/Employee/api/v1/entitytype/dynamic/update?EntityData

  ![](./Employee%20portal%20imgs/edit-entity%20typeFAQ.PNG)

# Task
  - A `task` generally refers to a specific piece of work or an activity that needs to be accomplished within a set period . 
  - Tasks are typically **part of larger projects, job responsibilities, or personal to-do lists .** 
    - They are specific actions or assignments that contribute to **_achieving a goal or completing a project ._**

## API


https://portal.mawarid.com.sa/Employee/api/v1/entitytype/field?EntityTypeId

# Requests
  - The term `request` refers to the act of asking for something or seeking assistance. In various contexts, a request can be a formal or informal expression of the desire or need for a particular action, information, service, or permission.

## API
 https://portal.mawarid.com.sa/Employee/api/v1/entitytype/field?EntityTypeId

**_Create API_**
  
   https://portal.mawarid.com.sa/Employee/api/v1/entitytype/form?EntityTypeId

 ![](./Employee%20portal%20imgs/create-requests.PNG)

**_Add API_**

https://portal.mawarid.com.sa/Employee/api/v1/entitytype/dynamic/insert?EntityData

 - This one Create - Request for Add the **_Iqama Number , Coordinator , CoordinatorEmail ,  Supervisor , Supervisor Email , Title , Description , Language , Request Type ._**

 - after Add the details successfully into the message .

# API Collection 

   - [Employee portal API](./Employee%20Portal.postman_collection.json).