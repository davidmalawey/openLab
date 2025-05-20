## Intro

Documentation about making documentation. Instructions for making Instructions, and so forth.

If you wish to be a contributor to documentation, you should know how to make top-tier docs.   Documentation is only worthwhile if it's treated like authoring a textbook or other publication that carries weight.  Hopefully it serves a purpose for 10 years or more, it's distilled to only actionable information, and we receive feedback to find errors & correct them.

## images
_best practices for images as of 2025.05_
You should see these features in the images across all of the documentation from 2024 forward, in openLabProject and our other open projects.

>
> **Quick list of best practices for images:**
> * use .jpg image type
> * use square aspect ratio
> * use resolution of 2048x2048
> * use multiple photos when the images need more detail
> * include tags in the image that relate to its context.
> * include img_descriptor with prefix "img_" if the file resides with many other files
> * include img_descriptor1 with number if the image has multiple images for the same purpose
>


Why select .jpg?
* the compression is typically better than .png
* it supports tags, for inclusion of keywords directly in the file (.png does not)
* ultimately, lighter web pages and faster loading

## accessibility
We should make it easy to navigate and this impacts both humans and AI agents.  Images and attachments should offer a trail back to their webpage, project, or other documentation online.  Names and tags and metadata all has the purpose of accessibility overall.

>
> **Quick list about PDF files**
> * include keywords that relate back to the main documentation
> * include a document title that is relevant, often matching the filename
> * include an author (you) if you made the publication and two authors if you have made modifications
> 

Images placed in the .md markdown text should include a brief description immediately before or after the image.  Images are only included when it adds some information to the text.  You may find some PDF files attached as hyperlinks in a text paragraph, and followed by one image that was snipped from the PDF.  This works like a thumbnail, to offer visual cues about the document so the reader can identify if they found the right document before they download.  We want to minimize the reader's effort to find the information they are seeking.  Important images should be saved in the _img folder even if they are also hosted online somewhere.  This gives a unified documentation in the case of downloading the whole github repository. 

Files or images that are not described in the text should be excluded from the repository.  If we upload a duplicate image with a new filename, the old image is deleted.  So, every file in the repository serves a purpose.  


