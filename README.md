# BeSIP - Be-Secure Improvement proposals
It is the set of action plans and enhancement procedure to improvise the existing Be-Secure features.  As the Be-Secure is being the umbrella of open source security projects, tools, sandbox environments to perform security assessments and secure open source technology stacks this improvement plan will makes the the project towards an different dimension along with improved quality.

Since the benefits from open source are multi-fold and it is the way forward to develop capabilities through collaboration with open source community projects, this improvement plan are also focusing on the Open Source Tools.
<br><br>

# BeSIP type

BeSIP are separated into several types, and each has its own list of tasks, todos and related documentation.
Few of these are added below.

### **BeSIP - CodeQL** <br>
This Improvement plan will enhance the Be-Secure/besman capabilities with the addition of CodeQL tool.
CodeQL basically an analysis engine used by developers to automate security checks and security researchers for various analysis on vulnerabilities. This tool is developed by GitHub to automate security checks.

The pre-works are updated under [BeSman wiki for CodeQL](https://github.com/Be-Secure/BeSman/wiki/Analysis-on-CodeQL)<br>
Artifact tracker projects: [CodeQL role](https://github.com/Be-Secure/ansible-role-oah-codeql)
<br><p>
### **BeSIP - GitLab security** <br>

Improvment plan in integration with GitLab application. <br>
The pre-works are updated under [BeSman wiki for Gitlab-Security](https://github.com/Be-Secure/BeSman/wiki/Analysis-on-Gitlab-Security)<br>

### **BeSIP - Sonatype lift** <br>
Improvment plan in integration with Sonatype lift application. <br>
The pre-works are updated under [BeSman wiki for Sonatype-lift](https://github.com/Be-Secure/BeSman/wiki/Analysis-on-sonatype-lift)<br>


### **BeSIP - WhileSource Cure** <br>
The pre-works are updated under [BeSman wiki for WhiteSource-Cure](https://github.com/Be-Secure/BeSman/wiki/Analysis-on-WhiteSource-Cure)<br>

Improvment plan in integration with WhileSource Cure application.

<br><br>
# BeSIP Key terms

Key Teams related with BeSIP:

### Tracked projects:

*   Projects which are tracked by Be-Secure
*   Expecting atleast one pipeline for scanning

### Untracked projects

*   Projects which are not coming under Be-Secure
*   Create pipeline for such project

### Partial opensource projects.  

*   Can be Tracked or untracked.
*   It includes the OSS which contains non-open source part.
*   Todo: Identify a plan for this group

### bes-ql prefix

* This will indicate the bes environment with with codeQL scanner tool installed.
* While using this environment user will get environment with bes environment provision tool and a CodeQL scanner
* eg. ```bes-ql-javaspring-dev```
