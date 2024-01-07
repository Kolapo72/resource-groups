# resource-groups

<h3>Create Resource Group</h3>
<p>A resource group is a container that holds related resources for an Azure solution. The resource group 
  can include all the resources for the solution, or only those resources that you want to manage as a group.</p>
<li>Sign in to Azure Portal.</li>
<li>Use the search box in the portal, search Resource Group</li>
<li>Create Resource Group</li>
  
![create resource-groups](https://github.com/Kolapo72/resource-groups/assets/147263584/f4ac22c6-ec4f-4df4-8c37-8690d2fb7790)
Fill up the Basics sub-form;
<li> Select the Subscription</li>
<li> Enter a desired name for the Resource Group</li>
<li> Select US West as the region</li>
<li>Select Review + Create</li>
<li>Select Create. It will take a few seconds to create a resource group.</li>


<h3>Create Virtual Machine</h3>
<li>Sign in to Azure Portal.</li>
<li>Use the search box in the portal, search Virtual Machine</li>
<li>Create Virtual Machine</li>

<p>Fill up the Basics sub-form:
<h6>Under Project Details;</h6></p>
<li> Select the Subscription</li>
<li>Select the Resource Group</li>

<h6>Under Instance details;</h6>
<li>Enter desired name for the Virtual machine name</li>
<li>Choose Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 (for the Image).</li>
<li>Leave the other lists as defaults.</li>

<h6>Under Administrator account;</h6>
<li>Provide a username, such as azureuser (any desired name)</li>
<li>Create Password and Confirm it. The password must be at least 12 characters long</li>

<h6>Leave Inbound Port as defaults</h6>

<h6> Click Licensing box</h6>

<li>Select Review + Create</li>
<li>Select Create. It will take a few seconds to create a Virtual Machine with some needed resources such as
  Virtual Network, Network Interface, Disk, Subnet.</li>
