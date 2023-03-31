
# Popup Submit Forms

Abrir um popup na mesma opagina ao invés de abrir o link em uma nova guia ao enviar um formulário. 



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