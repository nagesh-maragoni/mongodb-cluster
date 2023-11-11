# Terraform-scripts
This folder consists of the required terraform files to launch GKE cluster with minimum 3 nodes and maximum 4 nodes.
All the required code to launch GKE cluster is provided in the above files But, make sure to change the required fields like:
   1. Location
   2. Project name/ID
   3. Clustername
   4. Networkname
   5. Subnets-ranges
   6. Machine-type
   7. Firewall protocol 

Just run the following command: 

```sh
terraform apply -auto-approve
```
It will take minimum 10mins to create the cluster.
Once the cluster is successfully created goto the gcp dashboard and lookout for the created cluster. We will find an option # CONNECT select it and it will provide a command to connect to the created cluster copy the command and run it on the terminal.
We will be connected to the kubernetes cluster.