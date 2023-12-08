> [!NOTE]
> Please fill the below checklist as per the contents of the Pull Request. 
> Mark "Not Applicable" as needed.

### Key Information

Deliverable Name (Enter JIRA Story Numbers - comma separated):

Deliverable Type

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)

Deliverable Complexity

- [ ] LOW
- [ ] MEDIUM
- [ ] HIGH


### Testing

- [ ] Unit testing document is attached.
- [ ] Positive / Negative testing done.
- [ ] Not Applicable

Additional comments: 

### Configuration

- [ ] Sanofi Naming conventions and best practices followed for Fields/Objects/Flows/Validation Rules, etc.  - [Reference](https://ts.accenture.com/:x:/r/sites/SanofiHealthCloud/Shared%20Documents/General/9_Developer%20Guidelines/Sanofi%20-%20SFDC%20Naming%20Conventions.xls?d=w56831bf8a67b4e88bd9f1925d476f991&csf=1&web=1&e=XDRSuT)
- [ ] Profiles do not include any FLS or CRUD permissions, most of the permissions are part of the Permission Sets.
- [ ] Description is added for all components.
- [ ] **Validation Rules:** Bypass logic has been added in Validation Rules.
- [ ] **Flows:** Entry criteria filters irrelevant records.
- [ ] **Flows:** Bypass logic is added in the entry criteria.
- [ ] **Flows:** Best practices are followed - [Reference](https://admin.salesforce.com/blog/2021/the-ultimate-guide-to-flow-best-practices-and-standards)
- [ ] Not Applicable

Additional comments: 

### Apex

- [ ] Sanofi Naming conventions followed for Apex Classes, Apex Triggers, etc.  - [Reference](https://ts.accenture.com/:x:/r/sites/SanofiHealthCloud/Shared%20Documents/General/9_Developer%20Guidelines/Sanofi%20-%20SFDC%20Naming%20Conventions.xls?d=w56831bf8a67b4e88bd9f1925d476f991&csf=1&web=1&e=XDRSuT)
- [ ] Code comments and change log as per the Apex Java Doc format.
- [ ] Best practices are followed to handle Governor limits. 
- [ ] Trigger Framework has been used wherever applicable.
- [ ] Coding standards are followed as per Sanofi guidelines - [Reference](https://ts.accenture.com/:p:/r/sites/SanofiHealthCloud/Shared%20Documents/General/9_Developer%20Guidelines/Sanofi%20-%20Developer%20Guidelines%20and%20Best%20Practices.pptx?d=w2a8e20101e4d4382b282878ce629ac77&csf=1&web=1&e=zDnagC)
- [ ] Exception handling and Logging has been implemented.
- [ ] Security best practices are followed to control data visibility.
- [ ] Not Applicable

Additional comments: 

### LWC

- [ ] Sanofi Naming conventions followed for Component Names and other metadata.
- [ ] LWC performance best practices are followed - [Reference](https://developer.salesforce.com/blogs/2020/06/lightning-web-components-performance-best-practices)
- [ ] LWC config file reviewed for correct targets.
- [ ] Description is added for all components.
- [ ] Not Applicable

Additional comments: 

### Integration

- [ ] Named Credential is used for Endpoint and other information.
- [ ] No hard-coded URLs or credentials in the code.
- [ ] Request and Responses are logged using the logging framework.
- [ ] Exception handling and Logging has been implemented.
- [ ] Necessary Framework classes are used for REST callouts and Platform Event publishing.
- [ ] Not Applicable

Additional comments: 

### Omnistudio (Omniscript, Data Raptor, Integration Procedure)

- [ ] Omniscript best practices are followed. - [OmniStudio Standard](https://help.salesforce.com/s/articleView?id=sf.os_omniscript_best_practices_8368.htm&type=5) / [OmniStudio for Vlocity](https://help.salesforce.com/s/articleView?id=sf.os_omnistudio_for_vlocity.htm&type=5) 
- [ ] Data Raptor best practices are followed. - [Reference](https://help.salesforce.com/s/articleView?id=sf.os_omniscript_best_practices.htm&type=5)
- [ ] Integration Procedure best practices are followed. - [Reference](https://help.salesforce.com/s/articleView?id=sf.os_integration_procedure_best_practices_54721.htm&type=5)
- [ ] Not Applicable

Additional comments: 

### Security

- [ ] No PII/PHI data in the code
- [ ] More to be added
- [ ] Not Applicable

Additional comments: 

### Code scan

- [ ] SonarQube Static Code analysis is successful without any critical/high category issues.

Additional comments: 

# Review Bypassed

- [ ] **I approve to bypass the review.**

> [!WARNING]
> Bypassing the review process should be done only in valid cases with proper justification.

**Justification**

- [ ] HotFix / Incident Fix
- [ ] Non-Technical change
- [ ] DevOps configuration
- [ ] Other (please add the justification in comments)
