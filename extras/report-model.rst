============
Report model
============

.. note:: This section is under construction. Please contribute!

The report model can be used to generate simple reports. The objective is to create a very simple object model that can be used for basic reports containing headers, paragraphs, simple tables and figures.

The supported output formats are HTML, Latex and plain text. Support for Word (OpenXML) and PDF is under consideration, but this will add dependencies to other libraries.

========== ================= ======= ====== =========== ===== =====
Item       Description       HTML    Latex  Plain text  Word  PDF
========== ================= ======= ====== =========== ===== =====
Header     Headers             Yes    Yes    Yes        
Paragraph  Text                Yes    Yes    Yes        
Table      Tables              Yes    Yes    Yes        
Image      Bitmap graphics     Yes    Yes    No         
Plot       Plot model          Yes    Yes    No         
Drawing    Vector graphics                   No         
Equation   Using Tex syntax                  No         
========== ================= ======= ====== =========== ===== =====

Example
=======

.. sourcecode:: csharp

    var report = new Report();
    // TODO
