<properties linkid="manage-services-hdinsight-get-started-hdinsight" urlDisplayName="Getting Started" pageTitle="Getting Started with HDInsight - Windows Azure tutorial" metaKeywords="hdinsight, hdinsight service, hdinsight azure, getting started hdinsight" metaDescription="Learn how to use the Windows Azure HDInsight service." umbracoNaviHide="0" disqusComments="1" writer="bradsev" editor="mollybos" manager="paulettm" />

<div chunk="../chunks/hdinsight-left-nav.md" />

# Getting Started with Windows Azure HDInsight Service (Tutorial)

<div class="dev-onpage-video-clear clearfix">
<div class="dev-onpage-left-content">
<p>This tutorial gets you started using Windows Azure HDInsight Service. HDInsight Service makes [Apache Hadoop](http://hadoop.apache.org/) available as a service in the cloud. It makes the HDFS/MapReduce software framework available in a simpler, more scalable, and cost efficient Windows Azure environment. In particular, HDInsight simplifies the configuring, running, and post-processing of Hadoop jobs by providing JavaScript and Hive interactive consoles. The JavaScript console is unique to HDInsight and handles Pig Latin as well as JavaScript and Hadoop file system commands. HDInsight also provides a cost efficient approach to the managing and storing of data. HDInsight Service uses Windows Azure Blob Storage as the default file system. </p>
<p>These samples are intended to get you started quickly learning and to give you an extensible testing bed to work through concepts. They provide you an easy way to create data sets of various sizes and allow running samples over the various sizes so you may observe the effects of data size on jobs as you get to learn your cluster.</p>
</div>
<div class="dev-onpage-video-wrapper"><a href="http://channel9.msdn.com/Series/Getting-started-with-Windows-Azure-HDInsight-Service/Enable-a-Windows-Azure-Preview-Feature-video" class="label">watch the tutorial</a> <a style="background-image: url('/media/itpro/services/videos/hdinsight-hero-180x120.png') !important;" href="http://channel9.msdn.com/Series/Getting-started-with-Windows-Azure-HDInsight-Service/Enable-a-Windows-Azure-Preview-Feature-video" target="_blank" class="dev-onpage-video"><span class="icon">Play Video</span></a> <span class="time">1:01</span></div>
</div>



##In this Tutorial

* [Enable the HDInsight Service](#subscribe)
* [Create a Windows Azure Storage account](#create)
* [Provision an HDInsight Service cluster](#provision)
* [Use the HDInsight Service dashboard and sample gallery](#dashboard)
* [Run a sample MapReduce program from the sample gallery](#sample)
* [Examine the sample MapReduce program output using the Interactive Console](#console)
* [Connect to Microsoft Business Intelligence Tools](#dataexplorer)
* [Next Steps](#nextsteps)

##<a name="subscribe"></a>Enable the HDInsight Service

To complete this tutorial, you need a Windows Azure account that has the Windows Azure HDInsight feature enabled, and you need to have Excel 2010 or 2013 installed.

- To create a free Windows Azure trial account in just a couple of minutes, visit [Windows Azure Free Trial](/en-us/pricing/free-trial/ "Windows Azure Free Trial"). For help creating an account, [watch the video](http://channel9.msdn.com/Series/Getting-started-with-Windows-Azure-HDInsight-Service/Create-a-Windows-Azure-Account/ "Watch the video").

- To enable the Windows Azure HDInsight preview, see <a href="/en-us/develop/net/tutorials/create-a-windows-azure-account/#enable" target="_blank">Enable Windows Azure preview features</a>

<div class="dev-callout"> 
<b>Note</b> 
<p>While the HDInsight Service is available as part of a Windows Azure Trial subscription, a trial subscription places limits on the amount of compute and storage resources available to you. For more information, see the <a href="http://www.windowsazure.com/en-us/pricing/free-trial/">Windows Azure Free Trial</a> page.</p> 
</div>

<p><b>
Up Next [GettingStartedTutorial_2](Create a Windows Azure Storage account) > </b></p>

[jar-syntax]: http://hadoop.apache.org/docs/current/hadoop-project-dist/hadoop-common/CommandsManual.html#jar
