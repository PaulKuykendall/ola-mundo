| Field Name | Type | Description | Example |
|---|---|---|---|
| Comment | String | User provided comment to provide context, justification, or plan of action for a result. Optional, will be null if not provided. | We're failing because xyz, we will fix soon. |
| RemedationDate | String | The date by which the control will be implemented. Expected in yyyy-mm-dd format. Optional, will be null if not provided. | 2024-08-01 |
| IncorrectResult | Boolean | Whether or not the user considers the result determined by the SCuBA tool to be incorrect. | false |
