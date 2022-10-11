# CBOvsRFCvsLCOM

Software metrics in object-oriented programming have been very useful to predict class fault–proneness over the years up till now there have been disparities of high levels of these software metrics is either a bad or a good thing for a software product. Also, changes in a software class can be an indicator of fault-proneness as suggested by reseachers. For this analysis, I extracted the software metrics of 10 top-tier Java open source projects (Hosted on GitHub) and performed a comparison with their commit history (software change). The analysis reveals the correlation that exists between software changes (commit history) and CK's Coupling Between Object Classes (CBO), Response For A Class (RFC), and Lack Of Cohesion Of Methods (LCOM).  The final result plot reveals that LCOM is more correlated to changes in a software project, Which suggest that classes with the highest changes are mostly classes with large LCOM. A future work would be having more test samples.  

Projects extracted were:

Dbeaver		https://github.com/dbeaver/dbeaver
Dubbo	https://github.com/apache/dubbo
Glide	https://github.com/bumptech/glide
Java	https://github.com/TheAlgorithms/Java
Lottie-android 	https://github.com/airbnb/lottie-android
MPAndriodChart	https://github.com/PhilJay/MPAndroidChart
Retrofit	https://github.com/square/retrofit
RxJava	https://github.com/ReactiveX/RxJava
Netty	https://github.com/netty/netty
Spring-framework	https://github.com/spring-projects/spring-framework

For Software metrics extraction, the resource used can be found here: https://github.com/mauricioaniche/ck

For the Commit History extraction, the resource can be found here: https://github.com/chongchunyong/Commit-Change-based-WCN

