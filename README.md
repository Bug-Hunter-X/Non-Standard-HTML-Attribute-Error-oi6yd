# Non-Standard HTML Attribute Error

This repository demonstrates a common yet easily overlooked error in HTML: using a non-standard attribute.  While many browsers might handle these attributes gracefully, they're not part of the HTML specification and can lead to unexpected behavior, validation failures, and compatibility problems.

**The Bug:** The example `bug.html` uses a custom attribute `data-custom-attr`. While `data-*` attributes are standard and widely used,  the specific attribute `data-custom-attr` is not defined by any standard, hence this example is not following best practices. 

**The Solution:** The `solution.html` replaces the custom attribute with a standard way of adding data using, in this case, the `alt` attribute for the purpose of the example, or using a `data-*` attribute that has a better semantic meaning.  Always refer to the relevant HTML specification for correct attribute usage.