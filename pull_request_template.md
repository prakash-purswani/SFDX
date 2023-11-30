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

- [ ] Unit testing document is attached
- [ ] Positive / Negative testing done
- [ ] Not Applicable

Additional comments: 

### Configuration

- [ ] Sanofi Naming conventions and best practices followed for Fields/Objects/Flows/Validation Rules, etc.  - (LINK TO BE ADDED)
- [ ] Profiles do not include any FLS or CRUD permissions, most of the permissions are part of the Permission Sets.
- [ ] Description is added for all components.
- [ ] Not Applicable

Additional comments : 

### Apex

- [ ] Sanofi Naming conventions followed for Apex Classes, Apex Triggers, etc.
- [ ] Code comments and change log as per the Apex Java Doc format.
- [ ] Best practices are followed to handle Governor limits. 
- [ ] Trigger Framework has been used wherever applicable.
- [ ] Coding standards are followed as per Sanofi guidelines - (LINK TO BE ADDED)
- [ ] Exception handling and Logging has been implemented.
- [ ] Security best practices are followed to control data visbility.
- [ ] Not Applicable

Additional comments : 

### LWC

- [ ] Sanofi Naming conventions followed for Component Names and other metadata.
- [ ] LWC performance best practices are followed - [Reference](https://developer.salesforce.com/blogs/2020/06/lightning-web-components-performance-best-practices)
- [ ] LWC config file reviewed for correct targets.
- [ ] Description is added for all components.
- [ ] Not Applicable

Additional comments : 

### Integration

- [ ] Named Credential is used for Endpoint and other information.
- [ ] No hard-coded URLs or credentials in the code.
- [ ] Request and Responses are logged using the logging framework.
- [ ] Exception handling and Logging has been implemented.
- [ ] Necessary Framework classes are used for REST callouts and Platform Event publishing.
- [ ] Not Applicable

Additional comments : 

### Omniscript

- [ ] To be added later
- [ ] Not Applicable

Additional comments : 

### Security

- [ ] No PII/PHI data in the code
- [ ] More to be added
- [ ] Not Applicable

Additional comments : 

### Code scan

- [ ] SonarQube Static Code Analysis is sucessful without any Critial issues

Additional comments : 

# Review Bypassed

- [ ] **I approve to bypass the review.**

> [!WARNING]
> Bypassing the review process should be done only in valid cases with proper justification.

**Justification**

- [ ] HotFix / Incident Fix
- [ ] Non-Technical change
- [ ] DevOps configuration
- [ ] Other (please add the justification in comments)
