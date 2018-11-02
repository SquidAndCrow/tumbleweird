# RE: Events

InDesign has an odd way of reading XML. It pays attention to tabs and line breaks, so the only ones that should be added to the imported xml file are ones that should be visible in layout. The sample file in this repo has the correct tabbing and line breaking. 

You'll notice that the first <event> element has a <date_header> element: that'll produce the dark date heading when the styles are applied. The png shows what this file renders out of in ID. 
