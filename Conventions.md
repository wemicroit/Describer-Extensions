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
<h2>Commits</h2>
<p>There are currently no conventions on how to commit. You can commit as often or as little as you like.</p>
<p>The only thing which we do ask is that you do commit you include a message which actually describes what is being changed and why.</p>
<hr />
<h2>Merges</h2>
<h3>Issue into another issue branch</h3>
<p>You free to merge however you see fit, ie merge commit, squish etc and there is no requirement that you have to use a pull request.</p>
<p>The reason for this is due to the other conventions</p>
<h3>Issue into a release</h2>
<p>This has to been performed via a pull request which will perform a squish of the commits. </p>
<p>The commit message is to be the #{IssueNumber} followed by a short summary ie same as the branch name. </p>
<h3>Issue into RC/RTM</h3>
<p>This is not allowed it needs to go via a release branch ie milestone.</p>
<h3>Release into RTM </h3>
<p>Just like into the release branch all commits must come via a pull request. </p>
<p>The difference here is that the merge commit method will be utilised to preserve a list of everything that has been changes. </p>
<h3>Release into RC</h3>
<p>This is not allowed it needs to go via the RTM branch.</p>
<h3>RTM to RC</h3>
<p>These merges are to opperate the same way as merging into RTm.</p>
<hr />

<h2>Pull Requests</h2>
<p>Upon completion of an issue a pull request is to be made which will merge the changes in the identified milestone/release.</p>
<p>Pull requests will only be merge by an administrator.</p>