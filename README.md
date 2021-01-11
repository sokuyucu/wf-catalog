# wf-catalog
## Aim
To simplify the process of creating a cluster from groundup with one click

## Process
In order for this workflow to operate succesfully, first it must be saved as a workflow template. If you dont save it as a workflow template it will not ask for input arguments such as:
1. Worker and master machine replicas
2. API token
3. Cluster name

After saving go ahead and submit your workflow, Argo will ask you about the input arguments.

## Contents
There are two different workflows:
1. full-cluster: asks for every detail as input parameters.
2. basic-cluster: asks only machine replicas.

Format: ![test 12](https://okuyucuscom.files.wordpress.com/2021/01/cloud.png)
