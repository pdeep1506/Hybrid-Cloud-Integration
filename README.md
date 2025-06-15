# Project 1: Hybrid Cloud Integration

## Overview

This project establishes a secure site-to-site VPN connection between Microsoft Azure and Amazon Web Services (AWS), enabling secure data transfer and communication between the two cloud environments.

---

### Technologies Used

* Microsoft Azure
* Amazon Web Services (AWS)

---

### Project Steps

#### **Azure Configuration**

1.  **Create a Virtual Network (VNet) and Subnet:** A VNet is created in Azure with a specific address space to host the required resources. A subnet is also created to segment the VNet. 
2.  **Create a VPN Gateway:** A VPN Gateway is established in Azure to facilitate a secure and encrypted connection to AWS over the internet. 
3.  **Create a Local Network Gateway:** A Local Network Gateway is set up in Azure to represent the AWS network, enabling correct traffic routing through the VPN tunnel. 
4.  **Create the Connection in Azure:** The final connection is established in Azure, linking the Azure and AWS networks. 

---

#### **AWS Configuration**

1.  **Create a Virtual Private Cloud (VPC) and Subnet:** A VPC and subnet are created in AWS to provide an isolated environment for AWS resources. 
2.  **Create a Customer Gateway:** A Customer Gateway is set up in AWS to establish the site-to-site VPN connection with Azure. 
3.  **Create a Virtual Private Gateway:** A Virtual Private Gateway is created and attached to the VPC to manage the VPN connection.
4.  **Create a Site-to-Site VPN Connection:** A secure, encrypted tunnel between AWS and Azure is established by creating a Site-to-Site VPN connection. 

---

### Final Status

The project has been successfully completed, and the VPN connection is active and stable.