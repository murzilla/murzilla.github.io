---
title: cv
order: 4
libraries: [jquery]
---
{::nomarkdown}
<div id="cvLoader">Please, wait. Loading cv from google docs <img src="/assets/img/kg.svg" class="kgLoader"></div>
<iframe src="https://docs.google.com/document/d/e/2PACX-1vQULOvZyG2KFl_9jaq2uiykYiJrR687i5dIJ_o-b86nK85IE7tnDCGbn_bSjW14zwNf89WHODtanOPB/pub?embedded=true" id="cvIframe"></iframe>
<script>
$('#cvIframe').on( 'load', function() {
  setTimeout( function(){
    $("#cvLoader").hide();
  }, 500);
});
</script>
{:/nomarkdown}

