# odooDia
Dia plugin to convert the UML code to readymade module of odoo




************************ INSTALLATION *********************************************
1)Download Dia
2)download codegen_openerp.py 
3)put the codegen_openerp.py file inside 
/usr/share/dia/python  OR    ~/.dia/python
4)Go to Dia >>Dialog >> Python Console
5)enter → import codegen_openerp
6)To check whether the openerp plugin is installed or not 
7)Go to File >> Export 
and find the file type :- PyDia Code Generation(OpenErp)(*.zip)
(NOTE: You might need to do import the codegen_openerp everytime you open new Dia)


************************* TRY IT ****************************************************

To try , you can use the uml_test.dia file 


1)Open the minuteSchema.dia file in dia
2)enable openerp plugin as instructed above
3)goto File>> export
4)Choose data type as PyDia Code Generation(OpenErp)(*.zip)
5)Click ok and you may see the openerp code when you extract the file
