# x-browser-issues

List of common cross-browser issues. Pull requests are welcome!

### JavaScript

Support for `navigator.language(s)`:

|                           	| Chrome 	| Firefox 	| IE 11 	| IE 10 	| IE 9 	| Safari 	|
|---------------------------- |--------	|---------	|-------	|-------	|------	|--------	|
| `navigator.language`       	| Yes    	| Yes     	| Yes   	| No    	| No   	| Yes    	|
| `navigator.languages`       | Yes    	| Yes     	| No    	| No    	| No   	| No     	|
| `navigator.userLanguage`    | No     	| No      	| Yes   	| Yes   	| Yes  	| No     	|
| `navigator.browserLanguage` | No     	| No      	| Yes   	| Yes   	| Yes  	| No     	|

Getting data attributes:

|                   	| Chrome 	| Firefox 	| IE 11 	| IE 10 	| IE 9 	| Safari 	|
|-------------------- |--------	|---------	|-------	|-------	|------	|--------	|
| `el.dataset`       	| Yes    	| Yes     	| Yes   	| No    	| No   	| Yes    	|

- Use `el.getAttribute('data-*')` instead.
