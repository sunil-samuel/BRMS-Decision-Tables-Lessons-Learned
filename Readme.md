<p align='right'>
<small>Sunil Samuel<br>
web_github@sunilsamuel.com<br>
http://www.sunilsamuel.com
</small>
</p>

**<h1 align='center'>BRMS :: Testing and Debugging for Decision Tables</h1>**

# Overview

Many BRMS (Drools) application uses Excel Decision Table to author rules.  Over the years of working with the BRMS engine as a Red Hat Architect, there were several issues that I ran into which seemed as brick walls at the time.  But in most cases, these ended up being something very simple.  I wanted to capture those issues for future projects.

There are several documentations in existence that shows how to create an application to use an Excel spreadsheet as the BRMS rules, just <a href="https://www.google.com/search?q=decision+table+spreadsheet+brms" target="_blank">Google It</a>.

So, I will try to document common issues that you will run into when using spread sheet decision tables on BRMS or Drools.

## Technology Stack

* BRMS - <a href="https://developers.redhat.com/products/brms/download" target="_blank">https://developers.redhat.com/products/brms/download/</a>
* Spreadsheet (OpenOffice or Excel)
* Cucumber 