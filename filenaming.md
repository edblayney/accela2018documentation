#File Naming 

**Script names should adhere to the following conventions with the exception of functions that exist in the /INCLUDES_CUSTOM folder:** 

EVENT;Group!Type!Subtype!Category.js 

**Example ** 

WTUA;Building!Comm!~!~.js 

**Notes** 

* Testing scripts should use the same name as the production script with a '_test' added before the extension. 

* Scripts placed in the /Scripts folder must use the indicated special characters to separate text. 

* Accela's import tool will translate the character into the proper code. Scripts made through the web interface do not require these special characters. 

~ = * 

! = / 

; = : 

A converted file name will appear as:  WTUA:Building/Comm/*/*  
