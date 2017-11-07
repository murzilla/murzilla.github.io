---
title: cv
order: 4
libraries: [jquery]
---
{::nomarkdown}
<div id="cvLoader">Please, wait. Loading cv from google docs <img src="/assets/img/kg.svg" class="kgLoader"></div>
<iframe src="https://docs.google.com/document/d/e/2PACX-1vQ4qSytR3Sl7VGCYPmeZp_xaS3tFUyWeIBoHxujIjVqyGTBjK7X3Wc17ZYblkIaSOkw3D-GYpOgBLGH/pub?embedded=true" id="cvIframe"></iframe>
<script>
$('#cvIframe').on( 'load', function() {
  setTimeout( function(){
    $("#cvLoader").hide();
  }, 500);
});
</script>
{:/nomarkdown}

