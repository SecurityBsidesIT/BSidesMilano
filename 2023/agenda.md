Location: NH Hotel Congress Center, Milano
------------
Time: 08/07/2023
------------
Website: [SecurityBSides Milano](https://milano.securitybsides.it)

[RECORDING LIVE STREAM](https://www.twitch.tv/securitycert/videos)

[YOUTYBE Playlist](https://www.youtube.com/playlist?list=PLPc5glBiLyN7L9ihZ4JNz2G9vwS4mO2ts)

Agenda
------------

Welcome and Intro
**SecurityBSides Italia Team**

11:00-11:10 Sala 1

Hacking Serverless Applications: A Treasure Map for Uncharted Waters
------------
**Matteo Rosi**

Serverless technology eliminates the need for development teams to provision servers, and it also results in some security threats being passed to the cloud provider. This frees up developers to concentrate on building logic and producing value quickly. But cloud functions still execute code. If the software is written poorly, it can lead to a cloud disaster. While Serverless code contains a mixture of cloud configurations and application programming interfaces (API) calls, legacy security solutions lack the context that is necessary in a serverless environment, and the consequence is a lack of observability and slower response times. This means that the security teams struggle to keep up with the speed of development and the security is left behind. Attackers, on the other-hand, take advantage of these uncharted waters to exploit serverless environments in the wild. In most cases we don't even hear about it because no one knows before something really bad happens. In this talk, we will discuss common risks and challenges in serverless environments as well as new attack vectors and common techniques attackers use to exploit Serverless applications. Finally, we will demonstrate how attackers can exploit newly discovered CVEs to target Serverless applications without being noticed.

[PDF]()

[VIDEO](https://www.youtube.com/watch?v=szKZ4zaNeaM)


11:10-12:00 Sala 1 

GraphQL Security Vulnerabilities in the wild
------------
**Antoine Carossio**

This groundbreaking research, involving a scan of over 1500 GraphQL endpoints, revealed a staggering 46,000+ security issues and sensitive data leaks, all accessible without authentication and with 10% classified as critical. In this session, Tristan and Antoine will share their unique testing methodology and delve into the most common GraphQL vulnerabilities unearthed during their research. They'll expose GraphQL-specific vulnerabilities, including complexity issues and schema leaks, alongside persistent standard API security threats like injections and server errors. They'll also highlight the often-underestimated problem of data leaks, including sensitive personal information and tokens. But, they won't leave you in the trenches; they'll showcase practical remediation strategies, introducing tools like GraphQL Armor and a handy security checklist for developers. This talk isn't just about raising alarms; it's about equipping you with the tools to secure your GraphQL applications. Leave with a newfound understanding of GraphQL's security landscape, a respect for its potential vulnerabilities, and a clear path to application safety.

[PDF](PDF/GraphQL_Vulnerabilities.pdf)

[VIDEO](https://www.youtube.com/watch?v=zPOQRpXOg80)

12:00-12:50 Sala 1 

Lunch
------------

13:00-14:00 

Facing the persian thief
------------
**Vito Alfano**

The speech talks about a lengthy investigation, which took a few months, in response to a security incident that struck a Middle Eastern entity, which revealed the existence of two different advanced persistent threats operating in the same context, with different ttps, but with the same scope: the silent exfiltration of data.

[PDF](PDF/Facing_the_Persian_Thief.pdf)

[VIDEO](https://www.youtube.com/watch?v=92FvxY-FOgc)

14:00-14:50 Sala 1 

ML Classification: Marvelous Universe of Models
------------
**Orlando Barrera II**

This Presentation relates to the classification of HTTP request data using machine learning models. The first example is text data (URLs) classification as either malicious (XSS) or benign, using a machine learning algorithm and data vectorization. https://github.com/obarrera/ML-XSS-Detection The second example is the classification of client side user behavior as either normal or anomalous. In the world of web applications security, code injection vulnerabilities account for a large portion of attack traffic. We will review the classification of data as malicious (XSS), attempting to inject scripts and code, or benign. This is not an easy problem to solve using traditional based approaches such as regex, signatures, parsing, or tokenization. Additionally, a significant amount of time and money is required to maintain updated lists of rules or modify parsing engines. The cat and mouse problem of bot traffic, scrappers, account takeover attempts, and other browser automation scripts is a major security concern. We will review the task of classifying a request as normal or anomalous using a machine learning model based on client side user behavior. The use of machine learning algorithms to create models to quickly classify data is becoming an ever more accessible solution. Using a limited dataset and a small group of features, simple classification machine learning examples will be shown. Is machine learning snake oil or a tool that can actually prove useful? Is it feasible to have a web app security machine learning core rule set (MLCRS) model library, similar to the OWASP ModSecurity Core Rule Set, that the community contributes to?

[PDF](PDF/ML_Classification_%20Marvelous_Universe_of_Models.pdf)

[VIDEO](https://www.youtube.com/watch?v=EHCD6ddMOJc)

15:00-15:50 Sala 1 

Pwning into Power System Application
------------
**Omkar Joshi**

Power system application is core of the entire power station eco-system. With this application anyone (with desired access) can modify stations parameters, can add station, can shut down stations or power itself etc. With this application we can control devices connected, automated baseline monitoring, remote access control, and automatic scheduled password changes, ultimately entire device management for most of the Scada. What if this application gets pwned? What if the application has bunch of vulnerabilities? What if attacker gets hold on the application and can shut down power stations? What if attacker can mess with the sub-stations and devices? We�re going to talk about � how attacker can intrude into environment and mainly pwn the power system application which ultimately will lead to take control of the devices, stations, entire power system etc. We�re going to discuss about our recent Red Team engagement in which we�ve hacked into the power system application and were able to do plenty of malicious activities. We�ll talk about several vulnerabilities which we found in one of the well-known Power System Application and they�ve compatibility with almost every manufacture and this is used in various SCADA organizations to connect the OT devices, centralized monitoring, management / administration of OT platforms. Final notes, we�ll talk about industry standard best practices, approach towards having zero trust and defense in depth

[PDF]()

[VIDEO](https://www.youtube.com/watch?v=PS8bSRzu6uk)

16:00-16:50 Sala 1 

Anti-Virus Evasion through BadUSB
------------
**Cristian Cornea**

During this presentation, we will take a look over how we can bypass most Anti-Virus detection using a payload embedded on a BadUSB device, resulting in a silver bullet for gaining initial access inside a victim network. Demo will be also included during the presentation.

17:00-17:50 Sala 1 

[PDF](PDF/Bypass_Anti_Virus_using_BadUSB.pdf)

[VIDEO]()


Workshops
------------
PLC_DoS
------------
**Omar Morando**

In this workshop I will explain how to attack an OT/ICS system composed of PLC and SCADA by exploiting some vulnerabilities of the Modbus protocol. We will use a physical laboratory with a plant simulator, a PLC and a Schneider Electric HMI system: you will learn how to write Python scripts to do a Man-in-the-Middle attack, Modbus data dumping, data flooding attack and PLC DoS.

10:30-13:00 Sala 2

[PDF](PDF/PLC_DoS_Workshop.pdf)

Semgrep
------------
**Claudio Merloni & Pieter De Cremer**

Between Agile, DevOps, and infrastructure as code, development is happening faster than ever. As a security team, it can be tough to keep up. We need to move fast, and iterate quickly as new issues emerge. SAST is one piece of a very important puzzle in the SDLC, so using tools effectively is the key to success! This workshop will be a hands-on masterclass by the creators and maintainers of Semgrep (https://github.com/returntocorp/semgrep), an open source, lightweight static analysis tool which can help enable development teams to scale their SAST efforts.

We'll cover:

- How to use Semgrep to start getting security coverage of all of your repos continuously in CI in minutes
- Best practices in rolling out continuous code scanning -- what to focus on, what to ignore, and how to maintain good working relationships with development teams
- How to use this scanning to enforce secure defaults across your org
- How to write custom Semgrep rules -- find anti-patterns and enforce security best practices unique to your organization
- We will show you how to use our dataflow (taint) engine, how you can write sources, sinks and sanitizers to identify vulnerabilities
- We will show new GA and experimental features we have been working on which are not widely adopted yet, and how you can write rules to fit your needs
- Advanced mode: We'll also show how Semgrep can be used like a Swiss army knife for a variety of purposes, as alerting you whenever a new route is added (new attack surface), when new dependencies are added or Dockerfiles are modified (detect potential supply chain risk), or when generally sensitive files are modified, such as core authorization logic or secret management
You'll leave this workshop with knowledge and skills you can immediately put into practice. For internal security engineers, you'll have new capabilities for scaling your company's security. For pen testers and offense-focused security professionals, we'll up your bug finding game to a new level.

Prerequisites

- You should be familiar reading and writing code in at least one programming language
- Bring a laptop with a web browser, IDE, git, and the ability to install CLI tools
- Familiarity with common vulnerability classes (e.g. OWASP Top 10) will be helpful but is not required.

14:00-17:00 Sala 2

[PDF](PDF/Semgrep_Workshop.pdf)