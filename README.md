# CircleCI
Documentation for CircleCI interview process.

## Start Using CircleCI Orbs

<p>Are you a CircleCI user who isn’t implementing Orbs? If so, let’s change that. Orbs are powerful tools that can simplify your workflow, and connect your work in CircleCI to other tools you might be using in your team.</p>
<p>Orbs are packages of CircleCI configurations that you can share, either within your organization or with the CircleCI community at large. In fact, there is an Orb Registry of these packages created by partners, the community, and within CircleCI  that are ready to use. If you can’t find what you’re looking for there, you can create your own Orbs, which are either private or shared with the CircleCI community. </p> 
<p>Here are a few of the primary advantages of using Orbs: </p>
<ul>
<li>Reduce configuration complexity</li>
<li>Integrate with your software</li>
<li>Stack services quickly and easily across projects</li>
</ul>
<p>But how much time will it take to get set up? So often in workplaces, the time it takes to implement a tool is what prevents its use. </p> 
<p>Fortunately, using Orbs is as simple as creating an Orbs key in your config file. That Orbs key is followed by the Orb slug, which includes the namespace and Orb name, and then the version number. With the Orb imported into the configuration file, that Orb’s elements are then available as <code>&lt;Orb-name>/&lt;element></code>.</p>
<p>These automated actions can increase the efficiency of your work. A quick glance at the Orb Registry demonstrates just a few of these capabilities. </p>
<p>The Orb circleci/slack@4.4.2 creates customized notifications specific to your needs, using built-in message templates or Slack’s visual Block-Kit builder. The Orb circleci/jira@1.3.1 reports the status of builds and deployments in CircleCI Projects to your Jira Cloud Instance. Either of these Orbs can help simplify communication or prevent duplication of effort for your team, and these are just two examples from a broad library available on the Orb Registry. You’ll also find Orbs like the AWS S3 Orb that copies a file or object to a new location. As previously mentioned, you can even create your own based on your needs. </p> 
<p>To start making your CircleCI work more effective, take another look at Orbs, and begin using them to improve your workflow. </p>
