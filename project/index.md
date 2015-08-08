---
layout: page
title: Project
---

[ASP.NET](#ASPNET)<br>
[IOS](#IOS)<br>
[Java](#Java)<br>
[Matlab](#Matlab)
<span id="ASPNET">
***
##ASP.NET Development
---
</span>

<span id="Timesheet">
###Timesheet System ([Demo](http://timesheetdemo.somee.com))<br>
_Jun. 2015 - Aug. 2015_| __C# / ASP.NET MVC4 / Entity Framework / CSS / jQuery__

It is an ASP.NET MVC application to manage employee’s personal information and work attendance. <br>
I implement following parts:

- Models of employee management, attendance management with ASP.NET MVC4 and Database First development using Entity Framework.
- UI and interactive tables enable sort and filter by multiple key words with CSS and jQuery.

<img src="image/Timesheet1.jpg" id="mainImg1" class="mainImgStyle">
<div id="div1" onclick="changeImg(event,'mainImg1')" class="imgStyle">
	<ul class="imgStyle"> 
	   	<li class="imgStyle"><img src="image/Timesheet1.jpg"/></li>
	    <li class="imgStyle"><img src="image/Timesheet2.jpg"/></li>
	   	<li class="imgStyle"><img src="image/Timesheet3.jpg"/></li>
	    <li class="imgStyle"><img src="image/Timesheet4.jpg"/></li>
	    <li class="imgStyle"><img src="image/Timesheet5.jpg"/></li>
	</ul>
</div>
</span>
<br>

<span id="EvalRpt">
###Online Course Evaluation Report
_Apr. 2015 - Present_ | __C# / Visual Studio / SQL Server__

It is a project for Measurement Evaluation Center, University of Houston.<br>
It is an ASP.NET Web Forms application to generate online course evaluation report for all the faculties and students.<br>
I implement following parts:

- Generate Online Course Evaluation Report with various questionnaires from different colleges/departments.
- Implement access control policy by Session State, to guarantee faculties can only view the report they authorized.

<img src="image/eReport1.jpg" id="mainImg2" class="mainImgStyle">
<div id="div2" onclick="changeImg(event, 'mainImg2' )" class="imgStyle">
	<ul class="imgStyle"> 
	   	<li class="imgStyle"><img src="image/eReport1.jpg"/></li>
	    <li class="imgStyle"><img src="image/eReport2.jpg"  /></li>
	</ul>
</div>
</span>

<span id="LogSheet">
###Log Sheet

_Apr. 2015_ | __C# / Visual Studio / SQL Server__

It is a project for Measurement Evaluation Center, University of Houston.<br>
It is an ASP.NET Web Forms application to manage the scanning log.<br>
I implement following parts:

- A GridView to insert, update, delete and validate records of scanning log. 

<img src="image/logsheet.jpg" id="mainImg3" class="mainImgStyle">

</span>

<span id="IOS">
***
##IOS Development
---
</span>
###FaceLock
_Mar. 2015 - May 2015_ | __Objective-C / Xcode / OpenCV__

It is a Computer Vition class project. There are four members in the group.<br>
It is an ISO application that implements 2D and 3D face detection and recognition. <br>
I implement following parts:

- IU. Implement with TableView, CollectionView, UIImageView.
- 2D face recognition based on LBPH algorithm.

<img src="image/FaceLock1.jpg" id="mainImg4" class="mainImgStyle">
<div id="div1" onclick="changeImg(event,'mainImg4')" class="imgStyle">
	<ul class="imgStyle"> 
	   	<li class="imgStyle"><img src="image/FaceLock1.jpg"/></li>
	    <li class="imgStyle"><img src="image/FaceLock2.jpg"/></li>
	   	<li class="imgStyle"><img src="image/FaceLock3.jpg"/></li>
	    <li class="imgStyle"><img src="image/FaceLock4.jpg"/></li>
	    <li class="imgStyle"><img src="image/FaceLock5.jpg"/></li>
	</ul>
</div>

<span id="Java">
***
##Java Development
---
</span>
###MapReduce Projects
_Feb. 2015 - May 2015_ | __Java / Eclipse / Hadoop / MapReduce / Hbase__<br>

__1. WordCount__

- Analyze the log from stackexchange.com, to compare average score of accepted answers with unaccepted answers. Input file is more than 10GB, and running time is less than 5 minutes.
-	Use Java and MapReduce library, and implement Chained MapReduce jobs.

__2. Hbase__

- Phase log from stackexchange.com, and perform a bulk import of the data in Hbase.
- Calculates the average number of answers per question from data in Hbase.

__3. Simple Search Engine__

- Analyze multiple thousand books as raw text files, we will build a simple search engine for identifying the most relevant books from given a search term. 
- Implement an inverted index.
- Build a simple retriever.

<span id="Matlab">
***
##Matlab Development
---
</span>
###Classification of U.S. Coins
_Nov. 2014 - Dec. 2014_ | __Matlab / Image Processing__<br>

It is a Digital Image Processing class project. There are five members in the group.<br>
This is a Matlab model to find out the total value of coins in the image.
<br>
I implement following parts:<br>

- Implement image-processing algorithms (color segmentation, circle Hough transformation) to extract coins’ feature.

<img src="image/Coin1.jpg" id="mainImg5" class="mainImgStyle">
<div id="div1" onclick="changeImg(event,'mainImg5')" class="imgStyle">
	<ul class="imgStyle"> 
	   	<li class="imgStyle"><img src="image/Coin1.jpg"/></li>
	    <li class="imgStyle"><img src="image/Coin2.jpg"/></li>
	</ul>
</div>

<script type="text/javascript">
	function changeImg(event, mainimg)
	{
		event = event || window.event;
		var targetElement = event.target || event.srcElement;
		document.getElementById(mainimg).src = targetElement.getAttribute("src");
	}
</script>
