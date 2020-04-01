# custodi

This is a project I wanted to started to apply the CIS check on Azure resources. 

## Purpose
CIS has the azure foundation benchmarks available at [this link](https://www.cisecurity.org/blog/cis-microsoft-azure-foundations-benchmark-v1-0-0-now-available/), which can be a good start to enhance the infrasturcture security. There are some project doing same things on github but mostly of of maintain. 

## Feature
1. Given a resource group name, costodi should be able to identity the resources and type of resources within that group. 
2. For each type of resources, custodi should be able to scan it base on the benchmark and generate report

## API
As start, costodi can be used from CLI only to get report generated, but in order to make this tool a better usage, rest API should be supported, and better with a web UI to see the report
