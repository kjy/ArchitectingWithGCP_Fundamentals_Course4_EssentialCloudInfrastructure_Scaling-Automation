# ArchitectingWithGCP_Fundamentals_Course4_EssentialCloudInfrastructure_Scaling-Automation
Virtual Private Network (VPN).  Created 2 custom networks and associated subnetwork in different regions. Created VPN gateways in each network.  Established static routes to enable the gateways to pass traffic.  Configured static routes to pass traffic to the VPN gateway.  Established firewall rules to enable ICMP and SSH traffic.   Performed most of the configuration from the command line. By configuring VPN manually, attained a better understanding of what GCP console does automatically so as to better troubleshoot a configuration.   



Virtual Machine Automation and Load Balancing.  Created a pool of VMs, web servers, and directed traffic to them through an external network.  Configured an external load balancer to use the pool, distributing work among the servers. Tested for high availability by placing a load on the service and stop a VM to simulate an outage by putting a bug in the code. Launched 2 more VMs in a secondary zone.  Configured an internal load balancer. Tested the internal load balancer for work distribution and availability.   



Autoscaler. Created a VM, then customized it by installing software and changing a configuration setting (making Apache start on boot). Used the custom image in an instance template, and then used the image template to make a managed instance group. After all the backend and frontend parts were connected together, stress-tested the system and triggered autoscaling using Apache Bench. Goal was to set up an HTTP(S) load balancer with autoscaling and verified that it was working.   



Infrastructure Automation.  Created an IAM service account. Create a VM.  Authorized a VM to use Google Cloud API, using the service account for purpose of creating automation tools.    Installed open-source software on the VM. Configured and tested the VM by deploying a Hadoop cluster.  Created a global solution by generating a snapshot of the boot disk with the service account already “baked in”.  Recreated the Clustermaker VM in a different region and tested it by deploying another Hadoop cluster in the new region.  Learned how to use IaaS skills that can be leveraged to automate activities through the Google Cloud SDK.  This is important for Site Reliability Engineering (SRE).  



Deployment Manager.  Downloaded and reviewed a set of Deployment Manager templates. Used the templates to Deploy 2 sub networks and a VM instance.

