# Paw-FileMakerInsertFromURLCodeGenerator

## What?
Code generator for `Insert from URL[...]` script step. 

## Why
The make the business of creating API calls from FileMaker a joyfully simple affair.

# How

- Install the extension from Paw (our favorite API tool here in the proof Kitchen). Look for 'FileMaker Code Generator' or the extension id, `com.proofgroup.PawExtensions.FileMakerCodeGenerator`
- Create your API request in Paw. Test it. `FileMaker Code Generator` will generate a section of code for the `Insert from URL` script step and a separate snippet for the URL of your request.
- Make sure the variables that are referenced by the generated code block are in your FileMaker script.
- You might also want to set a variable such as `$url` to store the url string snippet from the code generator. 
- Then, simply copy the `curl -X...` block from Paw to your `Insert from URL` step in FileMaker 

## Who
@ernestkoe (ernest.koe@proofgroup.com) + brian.ouimette@proofgroup.com

## Credits
Big props to Brian for doing the heavy lifting :). 

## Copyright & Licensing
This is an open source project (MIT License) brought to you by the proof dev Kitchen. Help us make it better.
