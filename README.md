# tfa-documentation
DHARMA Task Force A documentation

Epidoc Stylesheets adapted for the html display

## How to use the XSLT
- Go `Document>Validation>Configure Validation Scenarios...` or click on the `Configure Validation Scenarios` in the tools bar
- Create a new Scenario
- In the XSLT tab, set the value in XML URL as `${currentFileURL}` and in the XSL URL set the path toward  `*[write the path depending the set up of your computer]*/tfa-documentation/tfa-stylesheets/start-edition.xsl`
- In the Output tab, click on `save as` and set its value with the folder path and finish by `/${cfn}${date(yyyy-MM-dd)}.html`. The file will be save with the file name followed by the date and a html extension. Click on `Òpen in Browser/System Application`and on `Saved file` under it.
