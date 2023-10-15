---
layout: default
title: Home
nav_order: 1
description: "Homepage"
permalink: /
---

<div class="container">
	<div class="row">
		<div class="d-none d-md-block col-sm-3">
			<img src="{{'/assets/images/ranchen.jpg'| prepend:site.baseurl}}">
		</div>
		<div class="col">
			<p class="text-justify">
				Welcome to my homepage! 
			</p>
			<p class="text-justify">
				I am a postdoctoral researcher at the <a href="https://lids.mit.edu/">Laboratory for Information & Decision</a> <a href="https://lids.mit.edu/"> Systems</a> at Massachusetts Institute of Technology, working with Professor <a href="https://computing.mit.edu/martin-wainwright/">Martin J. Wainwright</a>. My research interests include reinforcement learning, data-driven decision-making, optimization, statistical machine learning, high-dimensional statistics, and nonparametric statistics, in terms of theoretical aspect, methodology aspect, and applications in business (revenue management in particular) and healthcare. 
<!---				I am a postdoctoral researcher at the <a href="https://lids.mit.edu/">Laboratory for Information & Decision</a> <a href="https://lids.mit.edu/"> Systems</a> at Massachusetts Institute of Technology, working with Professor <a href="https://computing.mit.edu/martin-wainwright/">Martin J. Wainwright</a>. My research interests include reinforcement learning, high-dimensional statistics, optimization, and nonparametric statistics, in terms of theoretical aspect, methodology aspect, and applications to data-driven decision making in business and healthcare. ---> 
<!--- lies in optimization and reinforcement learning for data-driven decision making, in terms of both the theorectical aspect and applications in business and health care. --->
			</p>	
			<p class="text-justify">
				I obtained my Ph.D. degree from the <a href="https://statistics.wharton.upenn.edu">Statistics and Data Science Department</a> at the Wharton School of the University of Pennsylvania. I have the fortune working with Professor <a href="http://www-stat.wharton.upenn.edu/~tcai/">Tony Cai</a> and Professor <a href="https://statistics.wharton.upenn.edu/profile/lzhao">Linda Zhao</a>. 
<!---				I obtained my Ph.D. degree from the <a href="https://statistics.wharton.upenn.edu">Statistics and Data Science Department</a> at the Wharton School of the University of Pennsylvania. I have the fortune working with Professor <a href="http://www-stat.wharton.upenn.edu/~tcai/">Tony Cai</a> and Professor <a href="https://statistics.wharton.upenn.edu/profile/lzhao">Linda Zhao</a>. --->
<!--- , under the supervision of <a href="http://www-stat.wharton.upenn.edu/~tcai/">Tony Cai</a>. --->
<!--- Previously, I earned B.S. in Pure and Applied Mathematics from <a href="https://www.tsinghua.edu.cn/en/Admissions/Undergraduate/Tsinghua_Xuetang_Talents_Program.htm">Tsinghua Xuetang Mathematics Program</a> at Tsinghua University.--->
			</p>
		</div>
	</div>
</div>

<br>


## Research Interests

- Data-driven Decision-making
- Reinforcement Learning
- Revenue Management
- Optimization
- High-dimensional Statistics
- Statistical Machine Learning
- Nonparametric Statistics


<!--- # - Reinforcement learning
<!--- # - High-dimensional Statistics
<!--- #- Optimization
<!--- #- Revenue Management
<!--- #- Statistical Machine Learning
<!--- #- Nonparametric Statistics
<!--- # Causal Inference --->

<br>

## Contact

- Email: [ran1chen@mit.edu](ran1chen@mit.edu)
- Address: 32-D607, 77 Massachusetts Avenue, Cambridge, MA 02139
<!-- - [Google Scholar](https://scholar.google.com.hk/citations?user=k2uOCu0AAAAJ&hl=en&oi=ao)
 -->
<br><br>

<!-- ## Co-authors
<div>
	<div class="panel panel-default">
	  <div class="panel-body" id="coauthors">
	  </div>
	</div>
</div>

<script>
  function lastNameSort(a,b) {
    return a.split(" ").pop()[0] > b.split(" ").pop()[0] ? 1 : -1;
  };

  var pubs = {{ site.data.publications | jsonify }}, 
      coauthors = {{ site.data.coauthors | jsonify }};
  var authors = [];
  for (var pub, i = 0; pub = pubs[i++];) {
    var author_arr = pub.authors;
    for (var author, j = 0; author = author_arr[j++];) {
      if (author.name != "Junhui Cai") {
        authors.push(author.name);
      }
    }
  }
  sorted_authors = authors.sort(lastNameSort);
  var author_obj = {};
  for(var author, i = 0; author = sorted_authors[i++];) {
  	if(author in author_obj) {
  		author_obj[author]++;
  	} else {
  		author_obj[author] = 1;
  	}
  }
  var author_arr = Object
    .keys(author_obj)
    .map(k => ({ "name": k, "count": author_obj[k] }));
  var merged = author_arr
    .map(x => Object.assign(x, coauthors.find(y => y.name == x.name )));

  var parsed = "<p class='text-justify'>";
  for(var item, i = 0; item = merged[i++];) {
    parsed += '<a href="' + item.homepage + '" style="font-size:' + (1)*15 + 'px">' +
        item.name + '</a>';
    if(i < merged.length) {parsed += ",\t ";}
  }
  parsed += "</p>";
  $("#coauthors").html(parsed);
</script> -->
