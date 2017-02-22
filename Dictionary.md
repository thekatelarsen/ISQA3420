# Dictionary

<b>Entities</b>
<ul>
<li><i>Manager:</i> The corporate manager who can request license and vulnerability results as well as create, edit, and apply policies.</li>
<li><i>Developer:</i> The corporate developer who can submit a software package to be scanned as well as request license and vulnerability results.</li>
</ul>
<b>Processes</b>
<ul>
<li><i>Create/Edit Policy:</i> The manager is able to create a new policy or edit an existing policy.</li>
<li><i>Apply Policy:</i> The manager is able to apply a policy to a package and receive the policy info back. </li>
<li><i>Query Database for License and Vulnerability Info:</i> The developer and manager are able to request license and vulnerability results from the license and vulnerability results database.</li>
<li><i>Accept Software and Results:</i> </li>
<li><i>Scan Software:</i> </li>
</ul>
<b>Data Stores</b>
<ul>
<li><i>NIST Vulnerability Database:</i> Stores the Vulnerability Results by package name.</li>
<li><i>License and Vulnerability Results Database:</i> Stores the License and Vulnerability results by package name.</li>
<li><i>Policy Databse:</i> Stores the policy name and info.</li>
</ul>
<b>Data Flows</b>
<ul>
<li><i>New Policy Info:</i> The new policy info to input into the policy database.</li>
<li><i>Policy Name:</i> The name of the policy to be edited.</li>
<li><i>Policy Info:</i> The policy info to be edited.</li>
<li><i>Edited Policy Info:</i> The edited policy info sent back to the policy database.</li>
<li><i>Package Name:</i> The name of the software package.</li>
<li><i>L Results:</i> The license results being sent to the developer and manager.</li>
<li><i>V Results:</i> The vulnerability results being sent to the developer and manager.</li>
<li><i>Software Package:</i> The actual package being sent to scan for licenses.</li>
</ul>
