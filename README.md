The index.html and styles.css files included in this repo have been modified for better accessibility and readability.

<strong>Overview of changes:</strong>
Non-semantic elements were largely renamed to semantic ones, except in some cases where it did not seem appropriate (the hero class div, for example)

The original css file had several classes that had identical function but different names. These were consolidated into a smaller number of unique classes. The html file was then modified to refer to these newly renamed classes.

In addition to replacing non-semantic with semantic elements, accessibility was also improved by adding alt text to all images.

Some sections of the original code used classes when it made more sense to use semantic elements, such as header, main, and footer. These classes were repurposed into css style code that modified these semantic elements. The html was adjusted to use these elements rather than divs with classes.

<strong>Resources:</strong>
URL to github website that functions off of refactored code: https://stiltskinner.github.io/01-HW-Code-Refactor/#online-reputation-management

Screenshot of github page functioning off of refactored code: <img src="Assets\Horiseon-Homepage-Refactored.png">