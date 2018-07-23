# ArcpyApplication

This is a Visual Studio template for ESRI arcpy python scripts.

I am using Visual Studio 2017. Maybe it works on older versions. (Why
would you want to use an older version?)

To use it, you can just download the pre-built zip file or you can
fork the project and make your own version.

## To build templates

Fork or clone this project. Open the solution in Visual Studio.

Under Project, use "Export Template".
I make both Project and Item templates because I use this template for both things.
I should make separate ones, I know. Someday I will do that.

I call one ArcpyApplication.py and the other ArcpyItem.py.
The Item template has only the PythonApplication.py file in it. The
Project template also has config.py in it.

The Export Wizard always forces you to put the zip files into
"%HOME%/Documents/Visual Studio 2017/My Exported Templates"

## To deploy templates

If you download the zip files, you can copy thme into your template
folders.  I think the default default is "%HOME%/Documents/Visual
Studio 2017/Templates", in Visual Studio I change it in
"Tools->Options->Projects and Solutions->Locations" to be on a network
drive so they are more portable and get backed up.

Drag each zip file into the appropriate folder. Restart Visual Studio.

If you build them, you can tell the Export Wizard to install the
templates when you build them. (It's the default.)

## To use templates

If you created both project and item templates and deployed them then they
will show up when you create new projects or when you add an item.

## Miscellaneous

I don't remember where I got the cute icon, maybe ESRI? If it belongs
to you and you don't want anyone using it, speak up and I will remove
it.
