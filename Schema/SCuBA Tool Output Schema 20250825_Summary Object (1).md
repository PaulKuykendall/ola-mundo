| Field Name | Type | Description | Example |
|---|---|---|---|
| Manual | Int | The number of manual checks needed for the baseline (e.g., controls that were not able to be assessed automatically). | 5 |
| Passes | Int | The number of controls that passed for the baseline. | 8 |
| Errors | Int | The number of controls that were unable to be evaluated due to an error during ScubaGear execution. | 0 |
| Failures | Int | The number of controls that failed that were marked as a "SHALL" requirement. | 15 |
| Warnings | Int | The number of controls that failed that were marked as a "SHOULD" requirement. | 3 |
| Omit | Int | The number of controls that were omitted from evaluation via the config file. | 3 |
| IncorrectResult | Int | The number of control results the user marked as incorrect in their config file. | 1 |
