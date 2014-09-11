---
title: syntax highlight cheatsheet
---
### ruby
{% highlight ruby %}
def show
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

### css
{% highlight css %}
@charset "UTF-8";
/*! normalize.css v3.0.0 | MIT License | git.io/normalize */
html { font-family: sans-serif; -ms-text-size-adjust: 100%; -webkit-text-size-adjust: 100%; }

body { margin: 0; }

article, aside, details, figcaption, figure, footer, header, hgroup, main, nav, section, summary { display: block; }

audio, canvas, progress, video { display: inline-block; vertical-align: baseline; }

audio:not([controls]) { display: none; height: 0; }

[hidden], template { display: none; }

a { background: 0 0; }

a:active, a:hover { outline: 0; }

abbr[title] { border-bottom: 1px dotted; }

b, strong { font-weight: 700; }
{% endhighlight %}

### javascript
{% highlight javascript %}
var _gauges = _gauges || [];
(function() {
  var t   = document.createElement('script');
  t.type  = 'text/javascript';
  t.async = true;
  t.id    = 'gauges-tracker';
  t.setAttribute('data-site-id', '503c5af6613f5d0f19000027');
  t.src = '//secure.gaug.es/track.js';
  var s = document.getElementsByTagName('script')[0];
  s.parentNode.insertBefore(t, s);
})();
{% endhighlight %}
