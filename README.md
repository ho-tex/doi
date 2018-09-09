You can hyperlink DOI numbers to dx.doi.org. Some publishers have elected to 
use some nasty characters in their doi numbering scheme (<, >, ; have all 
been spotted). This will either upset (La)TeX, or your pdf reader. This style 
file contains a user-level command \doi{}, which takes a doi number, 
and creates a hyperlink from it. The format of the doi can be controlled by 
redefining the \doitext command, which does not take an argument (unlike the
command with the same name in the doipubmed package). 

Note: the \doi{} command connot be used within other macros.

This style file is based original code written by Heiko Oberdiek 
and published on comp.text.tex. It was packaged with permission  
as a style file by Maarten Sneep, with some minor changes suggested 
by Bruno Voisin to accomodate the Apple pdf framework
Michael Orlov noticed that underscores were not handled appropriately 
and sends in a patch.

This code is placed under the LPPL.

Original discussion on Google under:
http://groups.google.com/group/comp.text.tex/msg/922919daa207d613

