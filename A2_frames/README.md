## Frames
### frmaeset
- frameset is 


### IFrame

> Adding the sandbox attribute to an `<iframe>` element places the element into sandbox mode, which adds the following 
> restrictions to how the browser treats the document inside the iframe:
> These sandbox precautions can help maintain browser security, which is especially useful if the `<iframe>` is embedding a third-party document over which you have no control.

Read more: https://html.com/attributes/iframe-sandbox/#ixzz7u3NzrGGu


- frame content is treated as being from a different origin than the primary document
- blocks form submission
- block JavaScript execution
- disable Pointer Lock API (mouse movement capture)
- prevents anchor links from targeting other browsing contexts (opening in a new tab or window)
- prevents use of plugins (`<embed>`, `<object>`, `<applet>`, or other)
- prevent the content from navigating its top-level browsing context
- blocks auto playback of media

### Sandbox attribute

<table>
<colgroup>
<col span="1" width="190">
</colgroup>
<thead>
<td>Value Name</td>
<td>Notes</td>
</thead>
<tr>
<td>allow-top-navigation</td>
<td>Allows a sandboxed iframe to navigate its top-level browsing context</td>
</tr>
<tr>
<td>allow-scripts</td>
<td>Re-enables JavaScript in a sandboxed iframe</td>
</tr>
<tr>
<td>allow-same-origin</td>
<td>Allows the content of a sandboxed iframe to be treated as having the same origin as the primary document</td>
</tr>
<tr>
<td>allow-popups</td>
<td>Re-enables popups in a sandboxed iframe.</td>
</tr>
<tr>
<td>allow-pointer-lock</td>
<td>Re-enables the Pointer Lock API (mouse movement capture) in sandboxed a iframe.</td>
</tr>
<tr>
<td>allow-forms</td>
<td>Re-enables form submission in a sandboxed iframe.</td>
</tr>
</table>


