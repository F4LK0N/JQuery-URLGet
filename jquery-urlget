/*
 * URL Get v1.0 (2018/05/18)
 * by Otavio B. Soria (otaviosoria@gmail.com)
 *
 * This jQuery plugin search the param in the url and return the value of it or "" if the param are not found or don't have a value.
 *
 */
(function($) {
	$.urlGet = function(search){
		
		let url = window.location.search.substring(1);
		let params = url.split('&');
		let value = "";
		
		params.forEach(function(param){
			param = param.split('=');
			if(search===param[0] && param.length>1)
				value = param[1];
		});
		
		return value;
	};
})(jQuery);
