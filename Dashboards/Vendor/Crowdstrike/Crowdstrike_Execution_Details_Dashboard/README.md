# Apply the Crowdstrike Dashboards.
  The YAML files are intented to be used with terraform and applying them to the tenant. The Dashboard quick links are intended to be copied and pasted into the Dashboards section of any tenant.

#Instructions

1. Crowdstrike Execution Details Dashboard QuickLink or YAML Must have the https://github.com/observeinc/observe-field-content/blob/main/Dataset-definitions/Vendor/Crowdstrike/Crowdstrike_FDR_Logs_Dataset_definition applied first when pasting in this quicklink into the Dashboads section of the tenant. Make sure to copy the entire contents of the file before attempting to paste from clipboard into Dashboards.
  - You'll want to first apply the Crowdstrike FDR Logs as a filtered dataset and then modify each card to have the Filtered Dataset as its input. 


#Demo Video of applying the Crowdstrike Execution Details Dashboard with the Quicklink : https://drive.google.com/file/d/1H7IwJqjbz-n6ZoGCmD5PUnDxz4BZv3wZ/view?usp=sharing
