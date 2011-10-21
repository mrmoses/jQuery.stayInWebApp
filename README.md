This jQuery plugin will stop links from leaving full screen mode on iOS devices. Other side effects may be included.

	$(function() {
		$.stayInWebApp();
	});

This use only links with the class `stay`.

	$(function() {
		$.stayInWebApp('a.stay');
	});
	
Full links (starting with http) will still open in Safari, as well as links with `target="_blank"`.

- - - - - - - - - -	

Thanks to [Bryan Murdaugh and David Leininger](http://fivable.com) for the original starting script (mostly for discovering that self.location works).

Thanks to Ben Nadel for posting about how to [detect iOS full screen mode](http://www.bennadel.com/blog/1950-Detecting-iPhone-s-App-Mode-Full-Screen-Mode-For-Web-Applications.htm).