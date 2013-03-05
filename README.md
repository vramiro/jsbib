jsbib
=====

Javascript library to display bibtex json


Usage
=====

    <script>
      $(document).ready(function(){
        var data = ... read some json bibtex source ...
        var prefix = http://prefix/to/the/data' // prefix for links        
        var bib = new JSBib(prefix, data);        
        $('#bibtex').replaceWith(bib.PPList(bib.records));
      });
    </script>
