[//]: # (title: Create quality gate)

<var name="protectionrule" value="repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/managing-a-branch-protection-rule"/>

Using [quality gates](quality-gate.xml), you can configure the number of problems in your codebase that you can accept. 
For example, if you set a quality gate for ten problems, a build workflow will fail once the eleventh problem is 
detected. This use case shows you how you can configure %product% quality gate for local runs as well as using in GitHub 
Actions and Jenkins pipelines.

<tip>
You can configure other %product% features ad described in the <a href="features.xml"/> section.
</tip>

<tabs>
<tab id="quality-gate-use-case-github" title="GitHub Actions">
    <include src="quality-gate.xml" include-id="quality-gate-github-actions-chunk"/>
</tab>
<tab id="quality-gate-use-case-jenkins" title="Jenkins">
    <include src="quality-gate.xml" include-id="quality-gate-jenkins-chunk"/>
</tab>
<tab id="quality-gate-use-case-local" title="Local run">
    <include src="quality-gate.xml" include-id="quality-gate-local-run-chunk"/>
</tab>
</tabs>








