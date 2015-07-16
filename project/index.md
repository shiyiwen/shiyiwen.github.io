---
layout: page
title: Project
---

[ASP.NET](#ASPNET)<br>
[IOS](#IOS)<br>
[Java](#Java)
<span id="ASPNET">
***
##ASP.NET Development
---
</span>

###Online Course Evaluation Report
_Apr. 2015 - Present_ | __C#/Visual Studio/SQL Server__

It is a project for Mesurement Evaluation Center, University of Houston.<br>
It is an ASP.NET Web Forms application to generate online course evaluation report for all the faculties and students.<br>
I implement following parts:

- Generate Online Course Evaluation Report with various questionaire from different colleges/departments.
- Implement access control policy by Session State.
<img src="image/eReport1.jpg" id="mainImg1">
<div id="div1" onclick="changeImg(event)">
 <img src="image/eReport1.jpg" class="imgStyle" />
 <img src="image/eReport2.jpg" class="imgStyle" />

</div>

<br>
###Log Sheet

_Apr. 2015_ | __C#/Visual Studio/SQL Server__

It is a project for Mesurement Evaluation Center, University of Houston.<br>
It is an ASP.NET Web Forms application to manage the scaning log.<br>
I implement following parts:

- A GridView to insert, edit and delete records of scaning log.
- Validate data in code behind file, when insert or edit records.
![Alt text](image/logsheet.jpg "Screenshot of Log Sheet")

<span id="IOS">
***
##IOS Development
---
</span>
###FaceLock
_Mar. 2015 - May 2015_ | __Objective-C/Xcode/OpenCV__

It is a Computer Vition class project. There are four members in the group.<br>
It is an ISO application that implement 2D and 3D face detection and recogenition. <br>
I implement following parts:

- IU. Implement with TableView, CollectionView, UIImageView.
- 2D face recognition based on LBPH algrithm.

<span id="Java">
***
##Java Development
---
</span>
###MapReduce Projects
_Feb. 2015 - May 2015_ | __Java/Eclipse/Hadoop/MapReduce__<br>

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


<script type="text/javascript">
function changeImg(event)
{
	var images = document.getElementById("div1").getElementsByTagName("img");
	for(var i=0; i<=images.length; i++){
		images[i].onmouseover = function(){
			this.style.cursor='hand';
			this.style.borderColor = 'red';
		}

		images[i].onmouseout = function(){
			this.style.cursor='pointer';
			this.style.borderColor = 'blacks';
		}
	}

	event = event || window.event;
	var targetElement = event.target || event.srcElement;
	document.getElementById("mainImg1").src = targetElement.getAttribute("src");

}
</script>

<script type="text/css">
.imgStyle
{
	height: 100px;
	width: 100px;
	border: 1px solid black;
}
</script>