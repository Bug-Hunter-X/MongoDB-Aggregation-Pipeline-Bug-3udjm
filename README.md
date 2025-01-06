# MongoDB Aggregation Pipeline Bug
This repository demonstrates a common error in MongoDB aggregation pipelines where the pipeline stages are not correctly ordered or configured, leading to unexpected results.  The `bug.js` file contains the faulty pipeline, and `bugSolution.js` provides the corrected version.

## Problem
The initial pipeline incorrectly processes data, leading to inaccurate aggregation results.  The specific issue is in the pipeline stages and the filter used. 

## Solution
The corrected pipeline in `bugSolution.js` addresses the issue by correctly ordering and configuring the stages.