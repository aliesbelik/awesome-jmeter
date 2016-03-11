# JMeter Resources
A curated collection of resources covering JMeter and related issues and activities: plugins, integrations, ci, devops etc.

This list grew up from [my answer on stackexchange](http://sqa.stackexchange.com/a/2552/1842) and [this jmeter-related links collection](https://delicious.com/veslefrik/jmeter).

- [JMeter Resources](#jmeter-resources)
    - [Books](#books)
    - [Getting Started](#getting-started)
    - [Tutorials](#tutorials)
    - [Best Practices](#best-practices)
    - [Scripting](#scripting)
    - [DSL](#dsl)
    - [Distributions](#distributions)
    - [Plugins](#plugins)
    - [CI](#ci)
    - [Distributed Testing](#distributed-testing)
    - [Cloud Services / SaaS](#cloud-services--saas)
    - [Results Analysis](#results-analysis)
    - [Results Visualisation](#results-visualisation)
    - [JMeter Performance](#jmeter-performance)
    - [Tips & Tricks](#tips--tricks)
    - [IDE Integration](#ide-integration)
    - [Performance Testing](#performance-testing)
        - [Streaming Protocols](#streaming-protocols)
        - [Mobile Apps](#mobile-apps)
    - [Community](#community)
        - [Blogs](#blogs)
        - [Forums](#forums)
        - [News & Updates](#news--updates)
        - [Twitter](#twitter)
        - [Q&A](#qa)
- [Contributing](#contributing)

## Books

- [Apache JMeter: A Practical Beginner's Guide to Automated Testing and Performance Measurement for Your Websites](http://books.google.by/books/about/Apache_JMeter.html?id=nX8oKIEvUcYC) by Emily H. Halili ([Packt Publishing](https://www.packtpub.com/networking-and-servers/apache-jmeter))
- [Performance Testing With JMeter 2.9](http://books.google.by/books?id=fpWmv3wPT64C) by Bayo Erinle ([Packt Publishing](https://www.packtpub.com/application-development/performance-testing-jmeter-29))
- [Performance Testing with JMeter, 2nd Edition](https://books.google.by/books?id=6ditCAAAQBAJ) by Bayo Erinle ([Packt Publishing](https://www.packtpub.com/application-development/performance-testing-jmeter-second-edition))
- [JMeter Cookbook](https://books.google.by/books?id=gJUeBQAAQBAJ) by Bayo Erinle ([Packt Publishing](https://www.packtpub.com/application-development/jmeter-cookbook))
- [Maîtriser JMeter: Du Test de charge à Devops](http://samples.leanpub.com/maitriser-jmeter-du-test-de-charge-a-devops-sample.pdf) by Antonio Gomes Rodrigues, Bruno Demion (Milamber) and Philippe Mouawad ([Leanpub](https://leanpub.com/maitriser-jmeter-du-test-de-charge-a-devops))

## Getting Started

- [A Simple Load Test with JMeter @ Urban Insight](https://www.urbaninsight.com/2011/07/18/simple-load-test-with-jmeter)
- [Load Testing with Apache JMeter @ DevX.com](http://www.devx.com/webdev/Article/17950)
- [Your First JMeter Test @ InformIT.com](http://www.informit.com/guides/content.aspx?g=java&seqNum=269)
- [Performance testing with JMeter @ Atlassian Blogs](http://blogs.atlassian.com/2008/10/performance_testing_with_jmete/)
- [Getting Started With Apache JMeter @ DZone](https://dzone.com/refcardz/getting-started-with-apache-jmeter)

## Tutorials

- [JMeter Tutorial @ ArtOfTesting.com](http://artoftesting.com/performanceTesting.html)
- Load Testing your Applications with Apache JMeter by Keld H. Hansen: [@ JavaBoutique.com](http://web.archive.org/web/20120302160128/http://javaboutique.internet.com/tutorials/JMeter/), [@ jGuru.com](http://www.jguru.com/article/server-side/load-testing-with-apache-jmeter.html)
- [Using JMeter @ OnJava.com](http://www.onjava.com/lpt/a/3066)
- [Effective load testing with Apache JMeter](http://www.davegardner.me.uk/blog/2010/09/23/effective-load-testing-with-apache-jmeter/)
- Load Testing with JMeter: [part 1](https://lincolnloop.com/blog/2011/sep/21/load-testing-jmeter-part-1-getting-started/), [part 2](https://lincolnloop.com/blog/2011/oct/12/load-testing-jmeter-part-2-headless-testing-and-je/), [part 3](https://lincolnloop.com/blog/2012/sep/19/load-testing-jmeter-part-3-replaying-apache-logs/)
- Some thoughts on stress testing web applications with JMeter: [part 1](http://nico.vahlas.eu/2010/03/17/some-thoughts-on-stress-testing-web-applications-with-jmeter-part-1/), [part 2](http://nico.vahlas.eu/2010/03/30/some-thoughts-on-stress-testing-web-applications-with-jmeter-part-2/)
- [Concurrent, High Throughput Performance Testing with JMeter](http://planet.jboss.org/post/concurrent_high_throughput_performance_testing_with_jmeter)
- [Functional Testing with JMeter](https://www.packtpub.com/books/content/functional-testing-jmeter)
- [JMeter Resources @ InfoSec Institute](http://resources.infosecinstitute.com/search/?s=jmeter)
- [JMeter Tutorial @ tutorialspoint.com ](http://www.tutorialspoint.com/jmeter/)
- [JMeter Tutorial @ jmeter.net](http://www.jmeter.net/)
- [JMeter Tutorial for Load Testing: The ULTIMATE Guide](http://www.javacodegeeks.com/2014/11/jmeter-tutorial-load-testing.html)
- [RESTful API testing with JMeter](http://www.ibm.com/developerworks/cloud/library/cl-jmeter-restful/)
- [How to Hit Your RESTful Web Service Using JMeter](http://crunchify.com/how-to-hit-your-restful-web-service-using-jmeter-perform-a-simple-load-test/)
- [JMeter: Load Development LifeCycle] (http://gerardnico.com/wiki/jmeter/lifecycle)
- Load Testing with Apache JMeter @ DigitalOcean: [part 1](https://www.digitalocean.com/community/tutorials/how-to-use-apache-jmeter-to-perform-load-testing-on-a-web-server), [part 2](https://www.digitalocean.com/community/tutorials/how-to-use-jmeter-to-record-test-scenarios)
- [JMeter Tutorial @ Guru99](http://www.guru99.com/jmeter-tutorials.html)
- [JMeter Course @ udemy](https://www.udemy.com/learn-jmeter-from-scratch-performance-load-testing-tool/)

## Best Practices

- [JMeter Official Best Practices](http://jmeter.apache.org/usermanual/best-practices.html)
- [JMeter Best Practices @ BlazeMeter](https://docs.blazemeter.com/customer/portal/articles/1932776-jmeter-best-practices)

## Scripting

- [Beanshell vs JSR223 vs Java JMeter Scripting](http://blazemeter.com/blog/beanshell-vs-jsr223-vs-java-jmeter-scripting-its-performance)
- [Using Groovy in JMeter](http://jroller.com/isaaclevin/entry/using_groovy_in_jmeter)
- [Testing with Groovy: Using JMeter and Groovy for load testing](https://www.packtpub.com/sites/default/files/downloads/Testingwithgroovy.pdf)
- [JMeter: forget about BeanShell Sampler](http://habrahabr.ru/post/250731/)

## DSL

- [A Ruby based DSL for building JMeter test plans](https://github.com/flood-io/ruby-jmeter)

## Distributions

- [Apache JMeter: Official downloads](http://jmeter.apache.org/download_jmeter.cgi)
- [JMeter for Windows: Package for installation JMeter with Plug-Ins](http://sourceforge.net/projects/jmeterforwindows/)

## Plugins

- [JMeter Plugins list](https://docs.google.com/spreadsheets/d/1FYMw3zCMr2Y37QCG_vOyC3HyrLxxi7x5I3khWLj3isU/edit?usp=sharing)
- [JMeter Plugins: Custom Plugins for Apache JMeter](http://jmeter-plugins.org/)
- [UBIK Load Pack: Productivity extensions for Apache JMeter](http://ubikloadpack.com/)
- [AtlantBH Custom JMeter Components](https://github.com/ATLANTBH/jmeter-components/)

## CI

- Tools & Plugins
    - [JMeter Ant Task](http://www.programmerplanet.org/projects/jmeter-ant-task/)
    - [JMeter Maven Plugin](http://jmeter.lazerycode.com/)
    - [Jenkins Performance Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Performance+Plugin)
    - [Sonar JMeter Plugin](https://github.com/SonarCommunity/sonar-jmeter)
    - [Bamboo JMeter Aggregator Plugin](https://github.com/diegomansua/Bamboo-JMeter-Aggregator-Plugin)
    - [Lightning: JMeter performance testing integration with CI infrastructure](https://github.com/automatictester/lightning)
- Tutorials & Demo
    - [Automated performance testing using JMeter and Maven](http://blogs.atlassian.com/2009/10/automated_performance_testing_using_jmeter_and_maven/)
    - [Performance Tests with JMeter, Maven and Hudson](http://www.theserverlabs.com/blog/?p=280)
    - [CI with Jenkins, Git, Maven, Grunt, and JMeter](https://github.com/dzuluagaapigee/apigee-ci-jenkins-git-maven-jmeter)
    - [Continuous automated web tests using Jenkins and JMeter](https://www.linkedin.com/pulse/continuous-automated-web-tests-using-jenkins-jmeter-mahanta)
    - [Automating JMeter tests with Maven and Jenkins](https://blog.codecentric.de/en/2014/01/automating-jmeter-tests-maven-jenkins/)
    - How to automate JMeter tests with Maven and Jenkins: [part 1](https://ribblescode.wordpress.com/2012/04/16/how-to-run-jmeter-tests-with-maven/), [part 2](https://ribblescode.wordpress.com/2012/04/16/how-to-automate-jmeter-tests-with-maven-and-jenkins-hudson-8/)
    - JMeter Continuous Performance Testing (JMeter + Ant + Jenkins): [part 1](http://www.testautomationguru.com/jmeter-continuous-performance-testing-part1/), [part 2](http://www.testautomationguru.com/jmeter-continuous-performance-testing-part2/)

## Distributed Testing

- [JMeter Distributed Testing Step-by-step](http://jmeter.apache.org/usermanual/jmeter_distributed_testing_step_by_step.pdf)
- [How to do remote testing the 'proper way'?](http://wiki.apache.org/jmeter/JMeterFAQ#How_to_do_remote_testing_the_.27proper_way.27.3F)
- [JMeter Remote Testing](http://jmeter.apache.org/usermanual/remote-test.html)
- Dockerized
    - [Dockerized JMeter: A Distributed Load Testing Workflow](https://gist.github.com/hhcordero/abd1dcaf6654cfe51d0b)
    - [JMeter Docker Images](https://hub.docker.com/search/?isAutomated=0&isOfficial=0&page=1&pullCount=0&q=jmeter&starCount=0)
    - [Distributed JMeter testing using Docker](http://srivaths.blogspot.com/2014/08/distrubuted-jmeter-testing-using-docker.html)
- Testing in Cloud
    - Amazon
        - [jmeter-ec2: Run JMeter on Amazon’s EC2 Cloud](http://web.archive.org/web/20120209090437/http://www.http503.com/2012/jmeter-ec2/)
        - [Load Testing with JMeter and Amazon EC2](https://medium.com/@alttaf_untangl/load-testing-with-jmeter-and-amazon-ec2-e143a7350596)
        - [Performance Testing in the Cloud with JMeter & AWS](http://www.artofsoftwaredevelopment.com/performance/performance-testing-in-the-cloud-with-jmeter-aws)
        - [JMeter distributed testing with Amazon EC2](https://vedovini.net/2009/08/jmeter-distributed-testing-with-amazon-ec2/)
    - DigitalOcean
        - [Building your own JMeter Cloud using Digital Ocean, JMeter and Docker](https://docs.google.com/presentation/d/1Yi5C27C3Q0AnT-uw9SRnMeEqXSKLQ8h9O9Jqo1gQiyI/)

## Cloud Services / SaaS

- [flood IO](http://flood.io/)
- [BlazeMeter](http://blazemeter.com/)
- [RedLine13](http://redline13.com/)
- [Beatsoo!](https://beatsoo.org/)
- [OctoPerf](https://octoperf.com/)
- [CloudLoad.io](http://cloudload.io/)
- [CA App Synthetic Monitor](https://cloudmonitor.ca.com/en/feature/transaction-monitoring-web-application-testing.html)
- [HP StormRunner Load](https://saas.hp.com/software/stormrunner-load)
- [Loadster](http://www.loadsterperformance.com/)

## Results Analysis

- [JMeter Result Analysis](http://artoftesting.com/performanceTesting/resultAnaysis.html)
- [Suggestions and Recipes for Log Analysis](http://wiki.apache.org/jmeter/LogAnalysis)
- [Performance Testing: Analyzing JMeter Results](http://www.datazoo.de/articles/158/performance-testing-analyzing-jmeter-results/)
- [Loadosophia: service for storing and analysing performance test results](http://loadosophia.org/)
- [JAnalyser: browser based results analysis tool](http://janalyser.com/)
- [JMeter Result Analysis Plugin](https://github.com/afranken/jmeter-analysis-maven-plugin)
- [JMeter Results Analyser](http://sourceforge.net/projects/jmstats/)
- [Export to Excel and Analyse JMeter Results using Pivot Tables](http://alexandru-ersenie.com/2009/08/28/jmeter-results-analysis-using-pivot-tables-in-excel/)
- DB Result Collectors
    - [JMeter DBCollector Plugin](http://sourceforge.net/projects/jmeterdbcollect/)
    - [JMeter MySQLCollector Plugin](http://wiki.apache.org/jmeter/MysqlCollectorPlugin)

## Results Visualisation

- [Better JMeter Graphs: Statistical Aggregate Report](http://rubenlaguna.com/wp/better-jmeter-graphs/)
- [Plotting your load test with JMeter](http://www.metaltoad.com/blog/plotting-your-load-test-jmeter)
- [JChav: JMeter Chart History and Visualisation](https://github.com/d6y/jchav)
- [Real Time Results with InfluxDB & Grafana](http://www.testautomationguru.com/jmeter-real-time-results-influxdb-grafana/)
- [Create JMeter graphs with CMDRunner with powershell parallel execution](http://performancewebautoamtionother.blogspot.com.by/2015/12/jmeter-create-graphs-with-cmdrunner.html)

## JMeter Performance

- [JMeter Performance](http://wiki.apache.org/jmeter/JMeterPerformance)
- [JMeter Performance and Tuning Tips @ UBIK Ingenierie](http://www.ubik-ingenierie.com/blog/jmeter_performance_tuning_tips/)
- [JMeter Performance and Tuning Tips @ BlazeMeter](https://blazemeter.com/blog/jmeter-performance-and-tuning-tips)
- [Beanshell vs JSR223 vs Java JMeter Scripting](http://blazemeter.com/blog/beanshell-vs-jsr223-vs-java-jmeter-scripting-its-performance)

## Tips & Tricks

- [JMeter tips and tricks scratchpad @ WebWob](http://www.webwob.com/html/jmeter_tips.html)
- [Advanced JMeter Tips @ informIT](http://www.informit.com/guides/printerfriendly.aspx?g=java&seqNum=520)

## IDE Integration

- [Intellij IDEA IDE Plugin](https://github.com/ponomandr/jmeter-idea-plugin)
- [JMeter + Eclipse HOWTO](http://people.apache.org/~mkostrze/jmeter-eclipse/index.html)
- [NetBeans JMeter Kit](http://plugins.netbeans.org/plugin/49923/jmeter)
- [Using a Load Generator in NetBeans IDE](https://netbeans.org/kb/docs/java/profile-loadgenerator.html)

## Performance Testing

### Streaming Protocols

- [Easy and realistic Load Testing of HTTP Live Streaming (HLS) with Apache JMeter](http://www.ubik-ingenierie.com/blog/easy-and-realistic-load-testing-of-http-live-streaming-hls-with-apache-jmeter/)
- [Using JMeter to Load Test Live HLS Concurrency of Wowza Streaming Engine](http://www.realeyes.com/blog/2015/08/26/using-jmeter-to-load-test-live-hls-concurrency-of-wowza-streaming-engine/)
- [How to Load Test HTTP Live Media Streaming (HLS) with JMeter](https://www.blazemeter.com/blog/how-load-test-http-live-media-streaming-hls-jmeter)
- [Load testing HLS with Ruby JMeter](https://blog.flood.io/load-testing-hls-with-ruby-jmeter/)

### Mobile Apps

- [Record iOS application HTTP requests](http://www.testautomationguru.com/jmeter-record-ios-application-http-requests/)
- [BlazeMeter Mobile Recorder](https://guide.blazemeter.com/hc/en-us/articles/207420545-BlazeMeter-Recorder-Mobile-Recorder-)
- [Performance Testing for Native Mobile Apps @ Blazemeter](https://www.blazemeter.com/blog/view-webcast-performance-testing-native-mobile-apps)

## Extending JMeter

- [JMeter Developer Manual](http://wiki.apache.org/jmeter/DeveloperManual)
- [How to write a plugin for JMeter](https://jmeter.apache.org/extending/jmeter_tutorial.pdf)
- [How to build a JMeter plugin utilising groovy](http://artur.ejsmont.org/blog/content/how-to-build-a-jmeter-plugin-utilising-groovy)
- [How to create a plugin in JMeter](http://stackoverflow.com/questions/20422640/how-to-create-a-plugin-in-jmeter)
- [Custom JMeter Samplers and Config Elements](http://codyaray.com/2014/07/custom-jmeter-samplers-and-config-elements)

## Community

### Blogs

- [BlazeMeter Blog](https://blazemeter.com/blog)
- [Ubik Load Pack Blog](http://www.ubik-ingenierie.com/blog/)
- [JMeter Tips](http://jmeter-tips.blogspot.com/)
- [Quants: JMeter](http://alexandru-ersenie.com/category/jmeter/)
- [RedLine13 Blog](https://www.redline13.com/blog/recent-posts/)
- [Flood.io Blog](https://blog.flood.io/)
- [JMeter Blog @ Shantonu Sarker](http://shantonusarker.blogspot.com.by/p/jmeter.html)
- [JMeter Expert Blog](http://jmeter-expert.blogspot.com/)

### Forums

- [JMeter Nabble Forum](http://jmeter.512774.n5.nabble.com/)
- [JMeter SQAforums](http://www.sqaforums.com/postlist.php?Cat=0&Board=UBB54)

### News & Updates

- [JMeter @ Linkedin](https://www.linkedin.com/topic/jmeter)

### Twitter

- [@ApacheJMeter](https://twitter.com/apachejmeter)
- [@jmeter_plugins](https://twitter.com/jmeter_plugins)
- [@BlazeMeter](https://twitter.com/BlazeMeterhttps://twitter.com/BlazeMeter)

### Q&A

- [JMeter on stackoverflow](http://stackoverflow.com/questions/tagged/jmeter)
- [Russian-language chat of JMeter enthusiasts](http://is.gd/jmeterchat)

# Contributing

Contributions are welcome!
