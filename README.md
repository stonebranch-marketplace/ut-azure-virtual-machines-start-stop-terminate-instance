<p><strong>Azure Virtual Machines Start-Stop-Terminate-Instance</strong></p>
<p>This Universal Task enables users to utilize Azure Virtual Machine (VM) name, resource group, subscription ID &amp; access token as inputs for the start, stop, terminate, list and check status of Azure VMs.</p>
<p><strong>Key Features:</strong></p>
<ul>
<li>This task uses python requests module to interact with the Azure cloud platform.&nbsp;</li>
<li>It expands user ability to start/stop/terminate/check/list Azure VMs that belong to a subscription and resource group.</li>
<li>In Universal Controller (UC), this task reaches and stays in the success state until the Azure instance is completely started, stopped, or terminated.&nbsp;</li>
<li>Scheduling this task in UC with the right dependencies set up would start and stop EC2 instances based on business needs using a UC workflow.&nbsp;</li>
<li>This task helps to dynamically manage VM operations. It could potentially reduce the Azure VM running cost in the cloud.&nbsp;</li>
</ul>
<p><strong>Additional Information:</strong></p>
<p>Important: This task uses Azure Oauth2.0 access token for Azure API authentication. Users may need to use Universal Controller web services task to refresh the access token periodically.</p>

Please visit this link to find key features, prerequisites, installation instructions, configuration instructions, and examples of how to use this integration. 
<a href="https://docs.stonebranch.com/confluence/display/UC69/UAC+-+Azure+Virtual+Machines+Start-Stop-Terminate-Instance" target="_self">Azure Virtual Machines Start-Stop-Terminate-Instance</a>.&nbsp;</li>
