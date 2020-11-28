## ZUGFeRD/Factur-X Open Source Software

### Libraries

#### Python
* [factur-x](https://akretion.com/en/blog/akretion-publishes-an-opensource-factur-x-python-library) is a BSD-licensed library
#### PHP
* @gp has a [factur-x](https://packagist.org/packages/atgp/factur-x) library for PHP
#### Java
* [Konik](https://konik.io/) GPL Java and C# library for ZUGFeRD 1 
* [Mustang](http://www.mustangproject.org/) APL Java library for ZUGFeRD 1 and 2(=Factur-X), Command-line tool to extract and combine 

### PDF tools
#### Creation

* [Ghostscript](https://www.ghostscript.com/) can be used to create PDF/A files from other documents and ordinary PDF
* [LibreOffice](https://www.libreoffice.org/) is a open source office suite with good PDF/A-1 export
* [iText RUPS](https://github.com/itext/rups/releases) can be used, along with a good hex editor to inspect the PDF internal structure
* [MuPDF](https://mupdf.com/) for windows and linux, mutools show can display simple internal structures


### Validators
* [VeraPDF](http://verapdf.org/), validates PDF-A "only" but very good :-)
* The [CEN Schematron](https://github.com/CenPC434/validation/tree/master/cii/schematron) can be used to validate ZUGFeRD/Factur-X XML
* [Konik](https://konik.io/ZUGFeRD-Validierung/) only ZUGFeRD 1 and now part of a propriary product Zrechnung
* [FNFE](https://services.fnfe-mpe.org) uses [a odoo plugin](https://github.com/akretion/factur-x-validator) which is based on VeraPDF and the CEN Schematron
* The new [FerdMC checker](https://validator.zugferd.org/) is based on an outdated version of [ZUV](https://github.com/ZUGFeRD/ZUV/) and embeds VeraPDF and the CEN Schematron as well

### Other tools
#### ZUGFeRD/Factur-X Creating
* The open source accounting application [Fakturama](https://www.fakturama.info/)
* Open source OCR/invoice recognition [invoice2data](https://github.com/invoice-x/invoice2data/)
#### ZUGFeRD/Factur-X Consuming
* Open-source homebanking application: [Hibiscus](https://www.willuhn.de/products/hibiscus/)
#### Display
* The [XRechnung XSLT](https://github.com/itplr-kosit/xrechnung-visualization/releases) can be used to convert ZUGFeRD/Factur-X to HTML

#### Miscellaneous
* [Additional data](http://4s4u.de/additional_data) is a python project to support extensions for certain industries like logistics, adding additional information to structured invoices (e.g. the invoice is for kilometres and the additional data contains the amount of miles) 
* Philip Helger published some [XSLT to convert UN/CEFACT CII to UBL](https://github.com/phax/en16931-cii2ubl)
* There is a interesting [parser](https://github.com/svanteschubert/en16931-data-extractor) for the EN16931 specification documents 
