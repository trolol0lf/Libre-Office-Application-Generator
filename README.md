# Libre Office Application Generator 1.0

This is the current Version of my "Libre Office Application Generator"

It is a small tool to generate Raw-Applications from managed Templates, replacing Placeholders with User-defined Values.

It will search through Subfolders of ./Templates/.. and consider a Folder as Templatefolder if it contains "\_Anschreiben.odt".

It will open up the selected Templates for you to edit, save those changes if desired and generate Applications from the template by replacing the placeholders in the text of the template, saving it and all neighbouring files to that template to ./Generated/\*TemplateNameIfDesired-\*CompanyName/ ; Opening it up afterwards to work in the Application right away!



Since this is written as an Libre-Office-Basic-Macro it will generate warnings or might not even be usable unless you allow your Libre Office to execute Macros (you should set the Setting to "Always ask before executing" for safety or add the Generator.odt as trusted file!

No Viruses from my side guaranteed :) (that's what a hacker would say ô.ô)



Written in Basic (one hell of a language)

