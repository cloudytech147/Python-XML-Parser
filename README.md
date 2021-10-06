# Python XML Parser Tutorial

![Python XML Parse](https://secureservercdn.net/160.153.137.163/84g.4be.myftpupload.com/wp-content/uploads/2021/01/Python-XML-Parser-Tutorial-Read-xml-file-exampleMinidom-ElementTree-665x333.jpeg)

XML stands for Extensible Markup Language and like HTML, it is also a markup language. In XML, however, we do not use predefined tags but here we can use our own custom tags based on the data we are storing in the XML file.

An XML file is often used to share, store, and structure data because it can easily be transferred between servers and systems. We all know when it comes to data, Python is one of the best programming languages to process and parse it.

Luckily, Python comes with a Standard XML module that can parse XML files in Python and also write data in the XML file. This is called Python XML Parser.

In this Python tutorial, we will walk through the Python XML minidom and ElemetnTree modules, and learn how to parse an XML file in Python.

Python XML minidom and ElementTree module
The Python XML module support two sub-modules minidom and ElementTreeto parse an XML file in Python.

The minidom or Minimal DOM module provides a DOM (Document Object Model) like structure to parse the XML file, which is similar to the DOM structure of JavaScript.

Although we can parse an XML document using minidom, ElementTree provides a much better Pythonic way to parse an XML file in Python.

### XML File

For all the examples in this tutorial, we will be using the demo.xmlfile, which contains the following XML data:

### #demo.xml

```
<item>
    <record>
        <name>Jameson</name>
        <phone>(080) 78168241</phone>   
        <email>cursus.in.hendrerit@ipsumdolor.edu</email>
        <country>South Africa</country>
    </record>

    <record>
        <name>Colton</name>
        <phone>(026) 53458662</phone>
        <email>non@idmagna.ca</email>
        <country>Libya</country>
    </record>

    <record>
        <name>Dillon</name>
        <phone>(051) 96790901</phone>
        <email>Aliquam.ornare@Etiamlaoreetlibero.ca</email>
        <country>Madagascar</country>
    </record>
  
    <record>
        <name>Channing</name>
        <phone>(014) 98829753</phone>
        <email>faucibus.Morbi.vehicula@aliquamarcu.co.uk</email>
        <country>Korea, South</country>
    </record>
</item>
```

In the above example, you can see that the data is nested under custom <tags>. The root tag is <item>, which has <record> as a nested tag, which further has 4 more nested tags:

* <name>,
* <phone>,
* <email>, and
* <country>

### Parse/Read XML Document in Python using minidom
  
minidom is the submodule of the Python standard XML module, which means you do not have to pip install XML to use minidom.

The minidom module parses the XML document in a Document Object Model(DOM), whose data can further be extracted using the getElemetsByTagName()function.

To know more click on [Python XML](https://www.techgeekbuzz.com/python-xml-parser-tutorial/) with examples.  
