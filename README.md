# jq.autogrow
AutoGrow for &lt;textarea>, jQuery plugin

This is jQuery plugin, which allows &lt;textarea&gt;'s to automatically resize, to grow or shrink, according to the volume of text inside.

USAGE:
<code>
$("textarea").autoGrow({
                animate: {
                       enabled: true, // default is false
                       duration: "fast", // default: 200
                       complete: function() {},       // Default: null
                       step:     function(now, fx) {} // Default: null
               },
               maxHeight: "500px",                    // Default: null (unlimited)
           });
</code>
