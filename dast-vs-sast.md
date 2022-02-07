## Static and Dynamic Analysis Explained

![static-dynamic](https://github.com/paulveillard/cybersecurity-static-analysis/blob/main/img/dast_sast.jpg)

### Dynamic Code Analysis: A Primer

The development of a fully optimized and secure application or software requires a wide array of testing tools and analyzers to verify the quality of the application and to make sure that it is running as expected. There are several testing methodologies for analyzing an application’s performance and security – such as static code analysis, dynamic code analysis, or a combination of both. These methodologies are used during source code review for organizations’ applications or software.

In the current COVID-19 pandemic, we’ve seen a lot of businesses struggle with security and application functionality in production. For example, a Zoom outage showcased how a poorly developed or untested application can bring down a company’s reputation and raise questions about users’ data security and privacy.

To address these issues, organizations need to understand what dynamic code analysis is, the advantages of using this method and how it is different from static code analysis.

#### What is Dynamic Code Analysis?
Dynamic code analysis is the process of analyzing an application or software during execution. It is the practice of analyzing the source code for reliability, quality and security while the application or software is running.

Performing dynamic code analysis for an application helps developers and testers find issues related to the application’s integration with database servers, application servers and web services. It also provides an analysis of how the application interacts with these services.

The primary goal is to find bugs and vulnerabilities present in the application or software so they can be debugged. Dynamic code analysis also helps find other issues such as problems related to authentication, session management, framework configuration, runtime privileges, protocol parser and more. It is most effective when the application being tested is executed with sufficient test inputs to achieve all possible outputs.

#### How it Differs from Static Code Analysis
The main difference is that static code analysis looks at the source code of the application for hidden flaws and bugs.

Analyzing the source code helps to identify the security flaws and defects that can compromise the safety of your application. Static code analysis does not give a holistic view of the application, though, as it provides very little or no understanding of developer intent.

Detection of memory leaks, null pointer dereferencing and concurrency-related issues are difficult to identify through static analysis. To detect such errors, dynamic analysis must be performed.

Dynamic code analysis, as mentioned, debugs an application or software during execution. Since it deals with real input data, this method enables you to discover issues with interfaces, sessions, requests, responses, authentication and more, as it is happening.

Another difference between the two methods is that, in static code analysis, the tester has access to the application’s architecture, source code, and libraries used before they perform the analysis; it’s a white-box security test. On the other hand, dynamic code analysis is a black-box type – the tester has no prior information about the application, and all testing is performed during execution.
