# Resetto

My custom CSS reset. Down here is a list of its features:

+ Default font size is set to 10 pixels for all text elements and so it becomes easier to calculate relative units (ems and rems) for a better responsive typography and box element resizing;

  > For example, if you want to change font size from 16px (browser default) to 20px using relative units, you would have to set it to be 1.25rem. If the desired font size is 46px, it would be 2.875rem. This makes it harder to calculate how much relative unit should be applied to every specific situation.

  > Changing default font size to 10px makes it easier because it is very straight foward to multiply and divide by 10 (20px would be 2rem, 46px would be 4.6rem). This way relative unit caculations can also be easily applied to resize any box element in the DOM.

+ Padding and margin properties are set to zero for all box elements;

+ The value of *box-sizing* property is set to be *border-box*. This way all box elements' width and height properties (and min/max properties) includes content, padding and border;

+ Prevents horizontal scrolling by setting *overflow-x* to *hidden* and width to 100%;

+ Default font weight is set to normal;

+ Default font family is set to **Open Sans**.
