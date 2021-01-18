<h1>Basic Git</h2>
You must perform three tasks to fix faulty in the source code and make all tests passed. After you finish each task, please commit and push your changes (you MUST write a meaningful commit message to explain the changes committed) on the master branch. Here is the steps of performing these three tasks by group of three developers: Dev1, Dev2 and Dev3.
<ol>
  <li>Dev1,2,3 - clone the project to Eclipse, 
  		<ul>
  			<li>import as a project from Git</li>
  			<li>Right click on project, Configure > Convert to Maven project</li>
  			<li>Run the project with package goal, all tests should fail</li>
  		</ul>
  <li>Dev1,2,3 - performs task 1,2 and 3 seperately</li>
  <li>Dev1 - stage, commit and push your changes for task 1</li>
  <li>Dev2 - fetch, pull to sync changes, then stage, commit and push your changes for task 2</li>
  <li>Dev3 - fetch, pull to sync changes, then stage, commit and push your changes for task 3</li>
</ol>



<h3>Task 1: Increment Fix</h3>
Fix the faulty in Counter increment(). All code changes and relevant commits must be performed on the master branch.

<h3>Task 2: Decrement Fix </h3>
Fix the faulty in Counter decrement(). All code changes and relevant commits must be performed on the master branch.

<h3>Task 3: Reset Fix</h3>
Fix the faulty in Counter reset(). All code changes and relevant commits must be performed on the master branch.

<h2>Build & Run project on GitHub</h2>
To see the result of building and running test on Github, you can click on Action tab. GitHub Action is CI-CD pipeline provided by GitHub. It is similar to other CI-CD pipeline platform e.g. Travis CI, Jenkins etc. In this project, there is a workflow already defined namely Github Classroom. This workflow is used for auto grading purpose. Every time you push the code on your repository, this workflow will be queued to execute automatically. You have to ensure that after your team made the last commit to fix all faults, the execution of this workflow runs successfully without any error. 


<h2>Answer the following questions</h2>
<ul>
  <li>What is different between fetch and pull?</li>
  <li>What is happen if dev2 or dev3 does not pull the code before committing and pushing to git?</li>
  <li>...</li>
</ul>
