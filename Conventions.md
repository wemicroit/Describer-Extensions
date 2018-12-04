<h1>Conventions</h1>
<p>In an attempt to keep consistency across projects, a number of conventions are in place and as time goes on more will be added.</p>
<h2>Git</h2>
<h3>Branches</h3>
<p>All branches are to be created under the appropiate folder which are:</p>
<ul>
<li>fix - bug fixes etc</li>
<li>feature - adds something new</li>
<li>release - a milestone which includes multiple new features/fixes etc</li>
</ul>
<p>The naming of the branches are in all cases to be as follows:</p>
<ul>
<li>#{issueNumber}-{Short summary}
</ul>
<p>Where then following is true.</p>
<ul>
<li>Issue Number - the issue number on github. If there isn't one an issue needs to be created.</li>
<li>Short Summary - couple of key words which sums the issue up</li>
</ul>
<hr />
<h3>Commits</h3>
<p>There are currently no conventions on how to commit. You can commit as often or as little as you like.</p>
<p>The only thing which we do ask is that you do commit you include a message which actually describes what is being changed and why.</p>
<hr />
<h3>Merges</h3>
<h4>Issue into another issue branch</h4>
<p>You free to merge however you see fit, ie merge commit, squish etc and there is no requirement that you have to use a pull request.</p>
<p>The reason for this is due to the other conventions</p>
<h4>Issue into a release</h4>
<p>This has to been performed via a pull request which will perform a squish of the commits. </p>
<p>The commit title is to be the #{IssueNumber} followed by a short summary ie same as the branch name. </p>
<p>The commit description is to be a list of all the commits which are being merged in. Note this can be tided up etc.</p>
<h4>Issue into RC/RTM</h4>
<p>This is not allowed it needs to go via a release branch ie milestone.</p>
<h4>Release into RTM </h4>
<p>Just like into the release branch all commits must come via a pull request. </p>
<p>The difference here is that the merge commit method will be utilised to preserve a list of everything that has been changes. </p>
<h4>Release into RC</h4>
<p>This is not allowed it needs to go via the RTM branch.</p>
<h4>RTM to RC</h4>
<p>These merges are to opperate the same way as merging into RTm.</p>
<hr />
<h3>Pull Requests</h3>
<p>Upon completion of an issue a pull request is to be made which will merge the changes in the identified milestone/release.</p>
<p>Pull requests will only be merge by an administrator.</p>
<hr />
<h2>Files</h2>
<h3>NameSpace</h3>
<p>All files are to reside under the WeMicroIt namespace</p>
<p>To construct a full namespace use the following methodology:</p>
<ul>
<li>Organisation ie WeMicroIt</li>
<li>Platform ie Composer</li>
<li>Type of library ie Utils</li>
<li>Folder path</li>
</ul>
<hr />
<h3>Organisation</h3>
<p>All files are to be stored in a folder which corresponds to what they are ie Model, Extensions etc.</p>
<hr />
<h3>Structure</h3>
<p>End applications are to simply be wrappers which calls the corresponding libraries</p>
<p>Models are to reside in their own project which is referenced by the other libraries. </p>
<p>Utilities such as extension methods are to be a utils class library</p>
<p>SDK is to comprise of methods which allow for interaction between end applications ie consuming a restful service.</p>
<p>Template is simply be the definition of what goes into that document/project.</p>
<hr />
<p>Should you have any further questions feel free to reach out. </p>