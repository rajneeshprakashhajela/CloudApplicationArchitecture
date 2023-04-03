<h1>1. Scalability</h1>
<h1>2. Security</h1>
<h1>3. Reliability</h1>
<h1>4. Performance</h1>
<h1>5. Deployment</h1>


<h1> application Testing tool </h1>
<h2>SAST- SonarQube</h2> 
<h2>DAST - Veracode Dynamic Analysis </h2> 
<h2>SCA -Veracode</h2> 
<h2>IAST -Synopsys</h2> 
<h2>RASP-Runtime Application Self Protection - Imperva, Microfocus</h2> 



Static Application Security Testing (SAST)<br/>
Use-Cases of SAST:<br/>

Code review during development<br/>
Vulnerability Scanning for Quality Assurance<br/>
Pre-deployment testing<br/>

Dynamic Application Security Testing (DAST)<br/>
DAST mechanisms are typically used to identify vulnerabilities such as:

Data/input validation vulnerabilities
Injection attacks
Broken Session management
Insecure APIs

DAST Tool -> Veracode Dynamic Analysis

Interactive Application Security Testing (IAST)

Share
Application Security Testing helps organizations improve their comprehensive security posture by proactively identifying source code weaknesses and mitigating vulnerabilities as they arise. Unfortunately, despite the security practices followed to develop an application, weaknesses, and vulnerabilities are commonly found and arise due to several factors. As a result, a single mechanism to test security vulnerabilities is rarely adequate. To help with this, SAST, DAST, IAST, and RASP represent a collection of security testing mechanisms that help with monitoring and automated testing across various phases of an SDLC. 

In this article, we delve into details of the SAST, DAST, IAST, and RASP testing mechanisms, the purpose each of these mechanisms solve, and popular application security testing tools for each. 


Types of Security Testing Tools
Earlier, firms tested and fixed security issues at the end of the development process, which was considered inefficient due to the time and cost it took. In the modern technology landscape, organizations leverage the DevSecOps model to introduce security checks in the earlier phases of development, enabling instant feedback for rapid fixes. 

Given the complexity of modern web applications, software teams are recommended to have complete visibility over weaknesses when source code is pushed into a repository. To do so, automated testing mechanisms and tools are a much-needed boon. Besides ensuring security, automated security testing enables agility by early identification and remediation of security issues. 

The following section outlines various Application Security Testing methods and their importance in a software’s lifecycle.

Application Security Testing Mechanisms
One of the most recommended best practices is to ensure that application vulnerabilities are never left as an afterthought during the development cycle. Instead, organizations must address vulnerabilities throughout all development and deployment stages to reduce sensitive data exposure (fuzzing) and the chances of system compromise even while the application is not released for general usage.

A comprehensive application security testing process can be administered through several mechanisms that target different phases of a software development life cycle to ensure maximum accuracy in identifying threats and vulnerabilities.

Static Application Security Testing (SAST)
Static Security Analysis or Static Application Security Testing (SAST) involves analyzing an application’s source code before it is compiled to identify issues during initial development. Also known as White Box Testing, this security testing methodology does not require the application to run in production and gives developers real-time feedback while they write code.

Through intuitive graphical representation, SAST tools help developers navigate their code base for errors while pointing out where vulnerabilities are located. An essential feature of these tools is their capability to highlight malicious code and provide guidance on remediation with minimal human effort. 

Use-Cases of SAST:

Code review during development
Vulnerability Scanning for Quality Assurance
Pre-deployment testing
Some popular Static Analysis tools include:

SAST in IDE
Coverity SAST Tool
With SAST tools, for example, you can detect the discovered on December 9, 2021, Log4J CVE-2021-44228 vulnerability.


Dynamic Application Security Testing (DAST)
DAST Scanning involves analyzing the application’s source code to uncover runtime vulnerabilities that developers can’t identify during code review. Also known as Black Box Testing, this approach examines the application’s security posture from an attacker’s viewpoint. The mechanism relies on a database of known vulnerabilities, mimics an attack, and raises alerts in case of attack success. Additionally, a DAST scanner notes how the application responds during an attack, thereby reducing false positives and providing critical insights on enhancing existing security features and controls. 

DAST mechanisms are typically used to identify vulnerabilities such as:

Data/input validation vulnerabilities
Injection attacks
Broken Session management
Insecure APIs
Some popular DAST tools include:

Crashtest Security
Netsparker
Acunetix
AppKnox
Veracode Dynamic Analysis
Dynamic Application Security Testing (DAST)
Interactive Application Security Testing (IAST)
Interactive Application Security Testing (IAST) combines SAST and DAST techniques, enabling security checks across various development and deployment stages. While doing so, IAST tools continuously monitor applications to gather information about performance, functionality, and bug



![image](https://user-images.githubusercontent.com/43515480/229450036-16217f3c-42c3-43fa-a634-85c8a122afc8.png)
![image](https://user-images.githubusercontent.com/43515480/229450232-b7c6bfe8-f51e-43f1-b6b7-637df7cb909f.png)

