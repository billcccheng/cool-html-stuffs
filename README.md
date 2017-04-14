# Cool HTML Stuffs

## Checkbox without box and toggling with text color change

HTML
```
<input type="checkbox" id="cb_1" value="cb_val" name="cb_name">
<label for="cb_1">
    Checkbox_Label
</label>
```

CSS
```
#cb_1 {
	display: none;
}

label {
	background-color:#333; 
	color:#FFF; 
}

input[type="checkbox"]:checked + label {
    background: brown;
}
```
