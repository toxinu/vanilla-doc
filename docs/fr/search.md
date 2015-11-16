---
layout: page
title: Recherche
slug: recherche
lang: fr
---

<form action="/docs/fr/search.html">
	<input type="text" name="q" id="tipue_search_input" autocomplete="off" required>
</form>
<div id="tipue_search_content"></div>

<script>
$(document).ready(function() {
     $('#tipue_search_input').tipuesearch({
          'mode': 'live',
          'liveContent': '.main-content',
          'liveDescription': '.main-content',
     });
});
</script>