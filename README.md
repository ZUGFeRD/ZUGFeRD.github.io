
## ZUGFeRD

[ZUGFeRD](http://www.ferd-net.de/front_content.php?idcat=255&lang=4) / Factur-X is an open european PDF invoice metadata standard. ZUGFeRD invoices embed a XML structure into PDF and look and behave like ordinary PDFs but can also be parsed and paid automatically. ZUGFeRD version 2 matches Factur-X version 1.

### This page

ZUGFeRD.org is the incubator and communication hub for and around ZUGFeRD/Factur-X open source *projects*. Others may also be [around](open-source.md).
Our [repos](https://github.com/ZUGFeRD).
For *people* and commercial projects around ZUGFeRD there is the [ZUGFeRD-community](http://www.zugferd-community.net), which even has a forum. For an English forum please refer to the [ZUGFeRD Google Group](https://groups.google.com/forum/#!forum/zugferd). 

## ZUGFeRD/Factur-X Open Source Software

### Libraries

#### Python
* [factur-x](https://github.com/akretion/factur-x) is a BSD-licensed library
#### PHP
* @gp has a [factur-x](https://packagist.org/packages/atgp/factur-x) library for PHP
#### Java
* [Konik](https://konik.io/) GPL Java and C# library for ZUGFeRD 1 
* [Mustang](http://www.mustangproject.org/) is an APL Java library for ZUGFeRD 1 and 2(=Factur-X) and a command-line tool to extract and combine. It also offers a [server](https://github.com/ZUGFeRD/mustangserver) with REST API

### PDF tools
#### Creation

* [Ghostscript](https://www.ghostscript.com/) can be used to create PDF/A files from other documents and ordinary PDF and even [complete Factur-X](https://bugs.ghostscript.com/show_bug.cgi?id=696472) files
* [LibreOffice](https://www.libreoffice.org/) is an open source office suite with good PDF/A-1 export
* [iText RUPS](https://github.com/itext/rups/releases) can be used, along with a good hex editor to inspect the PDF internal structure, or a Windows-only [alternative](https://github.com/Uzi-Granot/PdfFileAnaylyzer)
* [MuPDF](https://mupdf.com/) for windows and linux, mutools show can display simple internal structures
* https://github.com/naiveHobo/InvoiceNet
* Open source OCR/invoice recognition [invoice2data](https://github.com/invoice-x/invoice2data/)


### Validators
* [VeraPDF](http://verapdf.org/), validates PDF-A "only" but very good :-)
* The [CEN Schematron](https://github.com/CenPC434/validation/tree/master/cii/schematron) can be used to validate ZUGFeRD/Factur-X XML
* [Konik](https://konik.io/ZUGFeRD-Validierung/) only ZUGFeRD 1 and now part of a propriary product Zrechnung
* [FNFE](https://services.fnfe-mpe.org) uses [a odoo plugin](https://github.com/akretion/factur-x-validator) which is based on VeraPDF and the CEN Schematron
* The new [FerdMC checker](https://validator.zugferd.org/) is based on [Mustang](https://github.com/ZUGFeRD/mustangproject/) and embeds VeraPDF and the CEN Schematron as well
* Philip Helgers open-sourve-valdator [Phive](https://github.com/phax/phive) can validate almost everything EN16931-y (including XRechnung but not covering PDF)

### Other tools
#### ZUGFeRD/Factur-X Creating
* The open source accounting application [Fakturama](https://www.fakturama.info/)
* [Factur-X extension for LibreOffice](https://github.com/akretion/factur-x-libreoffice-extension) is a LibreOffice extension to generate Factur-X invoices from LibreOffice Calc published under the GPL licence. Watch this [video tutorial](https://www.youtube.com/watch?v=ldD-1W8yIv0).
* [Odoo](https://www.odoo.com/) is an OpenSource ERP software that has an OpenSource module [account\_invoice\_factur-x](https://github.com/OCA/edi/tree/10.0) to generate Factur-X invoices and another OpenSource module [account\_invoice\_import\_factur-x](https://github.com/OCA/edi/tree/10.0) to import Factur-X invoices.
#### ZUGFeRD/Factur-X Consuming
* Open-source homebanking application: [Hibiscus](https://www.willuhn.de/products/hibiscus/)
#### Display
* The [XRechnung XSLT](https://github.com/itplr-kosit/xrechnung-visualization/releases) can be used to convert ZUGFeRD/Factur-X to HTML
* There is a [freeware viewer](https://www.ultramarinviewer.de/) for XRechnung based on these XSLTs, additionally 
* there is an [open source cross platform XRechnung viewer](https://github.com/jcthiele/OpenXRechnungToolbox) as well as
* an attempt for an [open source cross platform multi format viewer](https://quba-viewer.org) (also displaying ZUGFeRD/Factur-X PDF and XML)

#### Miscellaneous
* [Additional data](http://4s4u.de/additional_data) is a python project to support extensions for certain industries like logistics, adding additional information to structured invoices (e.g. the invoice is for kilometres and the additional data contains the amount of miles) 
* Philip Helger published a [java library to convert UN/CEFACT CII to UBL](https://github.com/phax/en16931-cii2ubl)
* There is a [OpenXRechnungToolbox](https://github.com/jcthiele/OpenXRechnungToolbox) to visualize and validate XRechnung and Leitweg-IDs
* There is an interesting [parser](https://github.com/svanteschubert/en16931-data-extractor) for the EN16931 specification documents 
