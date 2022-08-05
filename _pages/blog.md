---
layout: archieve
title: ""
permalink: /blog/
author_profile: true
redirect_from:
  - /blog
---

<script src="https://www.retainable.io/assets/retainable/rss-embed/retainable-rss-embed.js"></script>

<body

  <div id="retainable-rss-embed" 
  data-rss="https://medium.com/feed/@sharonashferguson"
  data-maxcols="3" 
  data-layout="grid" 
  data-poststyle="inline" 
  data-readmore="Read the rest" 
  data-buttonclass="btn btn-primary" 
  data-offset="-100"></div>

</body>

<!-- <body>
  <div id="myDIV" class="header">
  </div>
  <ul id="myUL">
  </ul> -->
  <!-- <script>
        // call the function to start execution
      get();

         <!-- // function that call the API to get the JSON data -->
      async function get() {
        var r = await fetch('https://api.rss2json.com/v1/api.json?rss_url=https://medium.com/feed/@sharonashferguson');
        var data = await r.json();

            <!-- // display your title in header -->
        document.getElementById("myDIV").textContent = data['feed']['title'];

            <!-- // iterate the array of items and call the newElement function which add the new list item -->
        for (var i = 0; i < data['items'].length; i++) {
            newElement(data['items'][i]['title']);
        }
    }

        <!-- // Create a new list item when clicking on the "Add" button -->
      function newElement(textContent) {
        var li = document.createElement("li");
        var t = document.createTextNode(textContent);
        li.appendChild(t);
        document.getElementById("myUL").appendChild(li);
    }
</script> -->
<!-- </body> -->

<!-- [View my articles on Medium](https://medium.com/@sharonashferguson/)  -->
