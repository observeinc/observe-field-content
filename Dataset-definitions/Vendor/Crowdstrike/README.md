# Apply the Crowdstrike Dataset definitions.
  This data is arriving from CRIBL Stream unmodified, so the data should look the same no matter how you are fetching it as long as it is unmodified. Some adjustments to the initial filter string might need to be made depending on how the data is arriving.

#Instructions

1. The first definition that you'll want to apply is the Crowdstrike_FDR_Logs_Dataset_definition.
     - On line 33 there is a commented out link. After creating the AID Master file, you'll want to go back to this definition and uncomment that line and link to the AID Master dataset here.
2. Apply the Crowdstrike_FDR_AID_MASTER_definition dataset. This dataset is built off of the Crowdstrike_FDR_Logs_Dataset_definition dataset so it will be the Input.(There is a good chance that you'll get an error creating this dataset due to the make resource expiry. You might need to adjust this to 1hr expiry to get the query to run and save the dataset and can adjust the expiry back later)
3. Apply the Crowdstrike_Detections_definition. This dataset is built off of the Crowdstrike_FDR_Logs_Dataset_definition dataset so it will be the Input. 
