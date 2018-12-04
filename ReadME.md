<h1>Describer</h1>
<h2>Summary</h2>
<p>This projects compromises multiple solutions which have been designed to add additional functionality to Visual Studio. </p>
<p>This additional functionality comes in 2 forms</p>
<ul>
<li>Template Pack</li>
<li>Code Snippet Pack</li>
</ul>
<hr />
<h2>Template Pack</h2>
<p>This pack adds in new templates to Visual Studio so that the user can easily create the appropiate external documentation documet.</p>
<p>These templates are all xml based and follow the convention XML Commenting Syntax.</p>
<hr />
<h2>Snippet Pack</h2>
<p>This pack provides the user with a quick easy method on inserting additional nodes to the documents created using the other extension.</p>
<p>For instance it will add the node selected as well as all the child nodes/attributes make it more efficent to document all in your porject.</p>
<p>An additional feature is that it provides code snippets so that you easily reference your external documentation.</p>
<hr />
<h1>Usage Guidelines</h1>
<p>Install the extension via Visual Studio Marketplace</p>
<p>Add a new document to your project. It is recomended to place them inside a docs folder at the root of your project.</p>
<p>Fill in the details of the first node.</p>
<p>Add additonal nodes as needed using the code snippet to speed things up.</p>
<p>Once completed, populate your source document with references to your xml documentation using the code snippets.</P>
<hr />
<h1>Contributing Guidelines</h1>
<h2>Undertaking an existing issue</h2>
<p>I welcome others to contribute towards these extensions by assigning an Issue to them selves, creating a branch from Develop named according the following convention:</p>
<ul>
<li>feature/#{issueNumber}-{Short summary}
<li>fix/#{issueNumber}-{Short summary}
</ul>
<p>In both those conventions the issue number corresponds to the issue number which these commits are addressing & the shory summary is to make it easier to work out what the branch is for.</p>
<p>Once an issue is believed to have been resolved a Pull request needs to be made to merge the branch back into the appropiate release branch</p>
<p>An administrator will review the code and if happy merge it into the release branch.</p>
<p>Please note any new functionality which is implemented needs to be unit tested as well as documented using the conventions in place</p>
<hr />
<h2>Bugs</h2>
<p>Please raise an issue for each bug you uncover, so that a developer can address it and follow the above procedure.</p>
<hr />
<h2>New Features</h2>
<p>Prior to working any new feature please create an issue for it and once it has been approved aka assigned to a MileStone, you can start working on it</p>
<p>We will in most scenarios approve any new features, however there can be scenarios where we will opt to start a new project/repo which references this one to avoid this project growing signifigantly in scope.</p>
<p>This is why we recomend you not starting on any new features untill they have been approved by an admin.</p>