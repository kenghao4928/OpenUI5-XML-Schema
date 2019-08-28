<h1 align="center" style="border-bottom: none;">OpenUI5 XML Schema</h1>
<p align="center">Syntactically correct XSD schemata of OpenUI5 for validation and auto-completion.</p>
<p align="center">
    <a href="LICENSE">
        <img alt="GNU GPLv3" src="https://img.shields.io/github/license/zypA13510/OpenUI5-XML-Schema?style=flat-square">
    </a>
</p>

## Usage
Include `xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"` and
`xsi:schemaLocation` pointing to the corresponding schemata in the root element
in your XML.

You should also have an IDE / editor plugin that supports XML validation and
auto-complete for this to be useful.

```XML
<?xml version="1.0" encoding="utf-8"?>
<mvc:View
    controllerName="io.github.zypa13510.OpenUI5XMLSchema.example"
    xmlns="sap.m"
    xmlns:mvc="sap.ui.core.mvc"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="
        sap.m https://zypa13510.github.io/OpenUI5-XML-Schema/sap.m.xsd
        sap.ui.core.mvc https://zypa13510.github.io/OpenUI5-XML-Schema/sap.ui.core.mvc.xsd
    ">
</mvc:View>
```

## Credits
This project uses schema created upstream by [emumanu](https://github.com/emumanu).
