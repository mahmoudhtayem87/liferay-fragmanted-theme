# Liferay fragmented Theme 

This project has been created with generator-liferay-fragments, to demostrate how we can build a Liferay Theme from any bootstrap template.

Steps:
[1] Develop your bootstrap based theme
[2] Scope your boostrap theme styles to "#wrapper"
[3] Compile your boostrap theme "SASS / SCSS" to css
[4] Use Liferay Tool Kit to generate a fragment collection
[5] Copy your compiled css to your fragment collection -> resources
[6] Create a fragment to add the style links to your page, and you can referance the files from your compiled styles which you have just copied by using [resource:<filename>]
 
