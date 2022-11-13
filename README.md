# Backtests
## Straddle Based
- [D5 only with 3.5 and 4.0 SCM ensemble](/zerodte/opposing/prod_no_pulsing_di_scm_4.5_5_straddle_min_di_duration_2022/plPlot.html)

<iframe frameborder="0" id="iframe1" src="/backtests/zerodte/opposing/prod_no_pulsing_di_scm_4.5_5_straddle_min_di_duration_2022/plPlot.html"></iframe>

## Time Based
- [D5 only with 3.5 and 4.0 SCM ensemble](/zerodte/opposing/prod_no_pulsing_di_scm_4.5_5_min_di_duration_2022/plPlot.html)

<iframe frameborder="0" id="iframe2" 
src="/backtests/zerodte/opposing/prod_no_pulsing_di_scm_4.5_5_min_di_duration_2022/plPlot.html"></iframe>


<script>
	let iframe = document.querySelector("#iframe1");

	iframe.addEventListener('load', function() {
		iframe.style.height = iframe.contentDocument.body.scrollHeight + 'px';
		iframe.style.width = iframe.contentDocument.body.scrollWidth  + 'px';
	});	
	
	let iframe = document.querySelector("#iframe2");

	iframe.addEventListener('load', function() {
		iframe.style.height = iframe.contentDocument.body.scrollHeight + 'px';
		iframe.style.width = iframe.contentDocument.body.scrollWidth  + 'px';
	});	
</script>