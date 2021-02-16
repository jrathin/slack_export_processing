# slack_export_processing
Process the JSON file structure from a Slack workspace export and extract information as .csv files

1. Read_Data - Convert Data to .csv files with User Meta, Channel Meta, workspace joins, channel joins, reactions, mentions, threads stored. Updating with cleaned version

2. Slack_to_HIN - Same data, but as a Heterogenous Information Network Format (HIN) {https://arxiv.org/pdf/2001.01296.pdf}
