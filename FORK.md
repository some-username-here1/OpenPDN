# Notes on the Fork

Forking a vivid software project is usually a bad thing and there are 
only few reasons when this action is considered legitimated.
The most common of those reasons is a licence change of the project - 
this is what happened here.
The main author of this great piece of software, Rick Brewster, decided 
to change the licence for all further releases of Paint.NET [1] making 
this version the last one to licensed under MIT Licence (with exceptions 
for Artwork and the GPC library, limiting the whole software to 
non-commercial distribution, see src/Resources/Files/License.txt).
Any further releases include the restrictive clause
"You may not modify, adapt, rent, lease, loan, sell, or create 
derivative works based upon the Software or any part thereof."
One year has passed since the last free sources of the project had been 
released, giving the authors time to change their minds.
Their decision has to be respected, but the OpenSource community still 
has to be able to build upon the last version of this powerful tool.

 ## Main goals of this fork are:
 * Linux port (which means porting it to mono basically)
 * replacing non-free parts (Artworks, General Polygon Clipper as those 
   are only usable non-commercially, making this non-free software in 
   the sense of OSI [2])
   
Of cause, all credits to the initial authors will remain, naturally new 
contributors will be credited as well.


[1] http://blog.getpaint.net/2009/11/06/a-new-license-for-paintnet-v35/

[2] http://opensource.org/docs/osd
