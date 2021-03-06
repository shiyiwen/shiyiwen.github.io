---
layout: page
title: Project
---

[AngularJS](#AngularJS)<br>
[ASP.NET](#ASPNET)<br>
[IOS](#IOS)<br>
[Java](#Java)<br>
[Matlab](#Matlab)
<span id="AngularJS">
***
##AngularJS Development
---
</span>
###Unit Converter ([Demo](http://www.unitconverter.site))<br>
_Fall 2015_ | __HTML5 / CSS3 / AngularJS__

- Providing online conversion of length, weight, area, volume and speed with great user experience.
- Using AngularJS to implement two way data-binding and refine the conversion result format with custom derivative.

<img src="image/UnitConverter.jpg" id="mainImg0" class="mainImgStyle">

<span id="ASPNET">
***
##ASP.NET Development
---
</span>

<span id="Timesheet">
###Timesheet System ([Demo](http://timesheetdemo.somee.com))<br>
_Summer 2015_ | __C# / ASP.NET MVC4 / Entity Framework / CSS / jQuery__

This is an ASP.NET MVC 4 web application to manage employee’s personal information and work attendance, based on the architecture of Fitiri’s TimesheetMS.<br>
I implement following parts:

- Models of employee management, attendance management with ASP.NET MVC4 and Database First development using Entity Framework.
- Visualized the timesheet records in interactive table and chart with CSS, jQuery and Google Chart API.

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
_Spring 2015 - Present_ | __C# / Visual Studio / SQL Server__

It is a project for Measurement Evaluation Center, University of Houston.<br>
It is an ASP.NET Web Forms application to generate online course evaluation report for all the faculties and students.<br>
I implemented following parts:

- Created dynamic table for online course evaluation report with various questionnaires from different colleges/departments using placeholder.
- Implemented access control policy by Session State, to guarantee faculties can only view the report they authorized.

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

_Spring 2015_ | __C# / Visual Studio / SQL Server__

It is a project for Measurement Evaluation Center, University of Houston.<br>
It is an ASP.NET Web Forms application to manage the scanning log.<br>
I implemented following parts:

- A GridView to insert, update, delete and validate records of scanning log. 

<img src="image/logsheet.jpg" id="mainImg3" class="mainImgStyle">

</span>

<span id="IOS">
***
##IOS Development
---
</span>
###FaceLock
_Spring 2015_ | __Objective-C / Xcode / OpenCV__

It is a Computer Vition class project. There are four members in the group.<br>
It is an ISO application that implements 2D and 3D face detection and recognition. <br>
I implemented following parts:

- IU. Implemented with TableView, CollectionView, UIImageView.
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
_Spring 2015_ | __Java / Eclipse / Hadoop / MapReduce / Hbase__<br>

__1. WordCount__

- Analyzed the log from stackexchange.com, to compare average score of accepted answers with unaccepted answers. Input file is more than 10GB, and running time is less than 5 minutes.
- Used Java and MapReduce library, and implement Chained MapReduce jobs.

__2. Hbase__

- Phased log from stackexchange.com, and perform a bulk import of the data in Hbase.
- Calculated the average number of answers per question from data in Hbase.

__3. Simple Search Engine__

- Analyzed multiple thousand books as raw text files, we will build a simple search engine for identifying the most relevant books from given a search term. 
- Implemented an inverted index.
- Built a simple retriever.

<span id="Matlab">
***
##Matlab Development
---
</span>
###Classification of U.S. Coins
_Fall 2014_ | __Matlab / Image Processing__<br>

It is a Digital Image Processing class project. There are five members in the group.<br>
This is a Matlab model to find out the total value of coins in the image.
<br>
I implemented following parts:<br>

- Implemented image-processing algorithms (color segmentation, circle Hough transformation) to extract coins’ feature.

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
