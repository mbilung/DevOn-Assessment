# Introduction 

This is my code for Task-1, DevOn interview process.

<h2>Problem Statement:</h2>

Create a successful Build Pipeline in Azure DevOps

<p1>create a hello world program and upload to git hub
pull from git hub
and execute the pipeline automatically when some code changes in GitHub.</p1>

<h2>My Solution:</h2>

<p2>I have used github and github actions to demonstrate the build process deploying a static website hosted on <a href="https://orange-river-0f4472903.azurestaticapps.net/">azure</a>. This static website is created using basic html and css and is hosted on azure static webapp.

My rationale to use github actions instead of azure devops is as follows:

<ol>
  <li>Microsoft doesn't provides a free build agent without a request (I have raised a rquest with Microsoft,not certain when will I get one)</li>
  <li>To Showcase the solution using github actions as an alternative to azure devops pieplines</li>
</ol>

Nevertheless, I have created the same project and build pipeline using <a href="https://dev.azure.com/etherpages/WebUI/_build?definitionId=2">Azure Devops</a> as well

</p2>


<h2>Usage:</h2>

<p3>
<ol>
  <li>Clone the repoistory in your local and create a branch feature/{sample-branch-name}</li>
  <li>Edit the required tags in the file index.html under the dist folder and push the changes to github. github actions gets triggered and you can view your changes navigating to the <a href="https://orange-river-0f4472903.azurestaticapps.net/">azure website</a></li>
  <li>Simultaneously <a href="https://dev.azure.com/etherpages/WebUI/_build?definitionId=2">Azure Devops Pipeline</a> will also get triggered</li>
</p3>
