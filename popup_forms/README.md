
# Popup Submit Forms

"Open a popup in the same page instead of opening the link in a new tab when submitting a form."


#### Code Variables
```
const targetValue = "DESCRIBE_POPUP_NAME"
```
#### Code forms
```
<form action="www.RedirectURL.com" method="POST target={targetValue} onSubmit="submit()">
```
#### Code Open Popup
```
function submit(){
     window.open('',targetValue,'toolbar=yes,menubar=yes,resizable=yes,status=yescom,scrollbars=yes,width=600,height=430');
}
```