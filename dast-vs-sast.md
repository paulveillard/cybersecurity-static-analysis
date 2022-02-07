# Static and Dynamic Analysis Explained

![static-dynamic](https://github.com/paulveillard/cybersecurity-static-analysis/blob/main/img/dast_sast.jpg)

## Dynamic Code Analysis: A Primer

The development of a fully optimized and secure application or software requires a wide array of testing tools and analyzers to verify the quality of the application and to make sure that it is running as expected. There are several testing methodologies for analyzing an application’s performance and security – such as static code analysis, dynamic code analysis, or a combination of both. These methodologies are used during source code review for organizations’ applications or software.

In the current COVID-19 pandemic, we’ve seen a lot of businesses struggle with security and application functionality in production. For example, a Zoom outage showcased how a poorly developed or untested application can bring down a company’s reputation and raise questions about users’ data security and privacy.

To address these issues, organizations need to understand what dynamic code analysis is, the advantages of using this method and how it is different from static code analysis.

### What is Dynamic Code Analysis?
Dynamic code analysis is the process of analyzing an application or software during execution. It is the practice of analyzing the source code for reliability, quality and security while the application or software is running.

Performing dynamic code analysis for an application helps developers and testers find issues related to the application’s integration with database servers, application servers and web services. It also provides an analysis of how the application interacts with these services.

The primary goal is to find bugs and vulnerabilities present in the application or software so they can be debugged. Dynamic code analysis also helps find other issues such as problems related to authentication, session management, framework configuration, runtime privileges, protocol parser and more. It is most effective when the application being tested is executed with sufficient test inputs to achieve all possible outputs.

### How it Differs from Static Code Analysis
- The main difference is that static code analysis looks at the source code of the application for hidden flaws and bugs.

Analyzing the source code helps to identify the security flaws and defects that can compromise the safety of your application. Static code analysis does not give a holistic view of the application, though, as it provides very little or no understanding of developer intent.

Detection of memory leaks, null pointer dereferencing and concurrency-related issues are difficult to identify through static analysis. To detect such errors, dynamic analysis must be performed.

Dynamic code analysis, as mentioned, debugs an application or software during execution. Since it deals with real input data, this method enables you to discover issues with interfaces, sessions, requests, responses, authentication and more, as it is happening.

Another difference between the two methods is that, in static code analysis, the tester has access to the application’s architecture, source code, and libraries used before they perform the analysis; it’s a white-box security test. On the other hand, dynamic code analysis is a black-box type – the tester has no prior information about the application, and all testing is performed during execution.

### Every Application Needs Dynamic Code Analysis
This form of code analysis is essential, as it tests the code in real-life scenarios. Unexpected errors caused by interaction with multiple application functions are hard, or even impossible to find using static analysis. These errors only become obvious during the integration of various components or interaction with the whole system on deployment. Therefore, a dynamic analysis should be performed once the software is functionally complete. Additionally, doing dynamic analysis will:

- Allow testers to perform application analysis without having access to the actual code.
- Reveal errors that can crash the program.
- Help testers ensure that the product/software works well.
- Help quality enhancement by taking into consideration any drawbacks.
- Require less expertise to perform; therefore, it is less expensive than static code analysis. Static code analysis requires an expert in the language in which the application has been developed.


### How to DIY Dynamic Code Analysis
Dynamic code analysis can be customized depending upon the application being tested. But here are a few generalized steps that go into a dynamic code analysis:

- 1) Identifying the scope of application: The first step is to define the scope of the application that needs to be tested. For example, if the application is a web app, then its scope should include all the URLs on which the testing is required.
- 2) Fuzz the input fields: The second step is to fuzz the input fields and look for any anomalous behavior in the application’s functionality. For example, check if the web app requires login with valid credentials to access some of its features. Then, the tester must try anything that doesn’t make sense in the context of the application’s behavior. This will help to find security flaws like broken authentication.
- 3) Find anomalies: The third step is to look for what is causing performance or functionality anomalies. Search and closely analyze the output for each input to single out the improper behavior of the application.
- 4) Try to breach more security areas: Once you’ve found an anomaly, the fourth step is to try to target the same parameter, input or functionality to gauge access and impact from that flaw. For example, if there exists an authentication bypass in the application, then check to see if it leads to increasing the privileges of users.
- 5) Repeat steps 2 and 4 for another input in the scope of application.
You can also use open source tools to conduct dynamic code analysis for your application, based on the programming language in which the application/software is built:

- 1. .NET
Microsoft IntelliTest
Pex and Moles

- 2. Java
Java PathFinder

- 3. C & C++
CHAP
KLEE

LLVM/Clang Sanitizers:

AddressSanitizer
MemorySanitizer
ThreadSanitizer
- 4. JavaScript
Iroh.js
Jalangi2

- 5. Python
CrossHair
Icontract
Scalene
typo

- 6. Rust
MIRI
puffin
stuck

Static and dynamic code analysis are both an essential part of an application’s audit, whether for web, mobile – any type of application can benefit. Both these methodologies can provide a comprehensive view of the performance and security of your application. Dynamic code analysis can help ensure the security of your application by uncovering vulnerabilities that can be exploited by bad actors if not patched. Static code analysis can scan your application for bugs. Both of these complement each other and, together, can protect your applications and software from cyberattacks.
