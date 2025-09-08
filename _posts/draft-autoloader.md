---
layout: post
title: "Autoloader: a user guide"
date: 2025-09-02
categories: [databricks, autoloader]
author: Connor Quinn
permalink: /autoloader/
---


Autoloader is one of the best bits of Databricks


We'll review some of the interesting corners of autoloader.

# Use run-once as part of a job.
Get the benefits of autoloader with minimal cost.

# Idempotency. 
Only files that were successfully written to Delta are capturing in the checkpoint. So just rerun the autoloader stream.

#  .options("cloudFiles.useManagedFileEvents", True) 
public preview

# Inspect state: SELECT * FROM cloud_files_state('dbfs:/chk/my_feed')


#  "cloudFiles.schemaEvolutionMode": "addNewColumns",     # or "rescue"

# If you already have a lot of files in a location, consider using COPY INTO for faster/cheaper performance and then includeExistingFiles=false


It is worth spending some time looking through the docs in depth to understand the options available: https://learn.microsoft.com/en-us/azure/databricks/ingestion/cloud-object-storage/auto-loader/option
s