jsbib
=====

Javascript library to display bibtex json

Usage
=====

<script>
    $(document).ready(function(){
        var data = ... read some json bibtex source
        var bib = new JSBib('http://prefix/to/the/data', data);        
        $('#bibtex').replaceWith(bib.PPList(bib.records));
</script>
