# GDPR_Automation

Overview:

Due to the General Data Protection Regulation(GDPR) introduced in the European Union, Salesforce is now required to verify that phone numbers are not listed on individual countries’ Do Not Call (DNC) lists. Mulesoft is used to expose APIs that will consume the DNC data and drive the data flow. There are 3 process APIs and 6 System APIs created in Mulesoft, and a scheduled job is created to process the DNC list.
This repo contains has SOAP UI Projects that contain Automated Test Suites created using Ready API to validate the following: (1) Test Suite to validate individual process and system API. (2) DNC List Flow (2) Org62 Subscriber Flow

List of APIs:

PhoneFormat API <br/>
PhoneIndexProcess API <br/>
PhoneIndexSystem API <br/>
DNCStatus Process API <br/>
DNCLookup SystemAPI <br/>
Org62DNCStatus System API <br/>
DNCListProcess API <br/>


