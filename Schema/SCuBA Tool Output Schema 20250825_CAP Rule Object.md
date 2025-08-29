| Field Name | Type | Description | Example |
|---|---|---|---|
| Name | String | The name of the conditional access policy (CAP). | Require Managed Device |
| State | String | The state of the conditional access policy, either "On" or "Report-only." | Report-only |
| Users | Array | An array with two strings: one describing the users included by the CAP, and one describing the users excluded by the CAP. | ["Users included: 2 specific users, 1 specific group","Users excluded: None"] |
| Apps/Actions | Array | An array of strings. The first string described the target of the CAP, either apps or actions. If the target is apps, there will be two other strings, one describing apps included and another describing apps excluded. If the target is actions, there is be just one other string describing the action. | ["Policy applies to: apps", "Apps included: All", "Apps excluded: None"] |
| Conditions | Array | A list of strings describing the conditions of the CAP. | ["Sign-in risk levels: high","Client apps included: all"] |
| Block/Grant Access | String | A description of the action to be taken for access attempts matching the CAP. | Allow access but require device to be marked compliant, OR Hybrid Azure AD joined device |
| Session Controls | Array | A list of strings describing the session controls to be applied. | ["Persistent browser session (never persistent)"] |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
|  |  |  |  |
