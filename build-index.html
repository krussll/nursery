<html>
<head></head>

<body>
<div id="log"></div>

 <script>
      window.title = [{% for p in site.nursery %}{"title": "{{ p.title | xml_escape }}","urn": "{{ p.urn | xml_escape }}","url": "{{ p.url | xml_escape }}"}{% unless forloop.last %},{% endunless %}{% endfor %}];
    </script>

    <script src="https://unpkg.com/lunr/lunr.js"></script>
    <script> 
      var idx = lunr(function () {
          this.ref('url');
          this.field('title');
          this.field('urn');


          window.title.forEach(function (doc) {
            this.add(doc)
          }, this);
        });
      
      document.getElementById('log').innerHTML = JSON.stringify(idx);
   </script>
</body>
</html>
