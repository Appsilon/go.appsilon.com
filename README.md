Appsilon URL tool: https://go.appsilondatascience.com/link/

Just add new directory with proper index.html file. 
You can choose between url masking (original page is in an iframe) or
visible redirection.


### Troubleshooting

Be aware that some websites prevent from displaying them inside iframe. When you see blank page
check browser console for the following error:

```
Refused to display 'https://app.asana.com/0/595107366583797/list' in a frame because it set 'X-Frame-Options' to 'sameorigin'
```