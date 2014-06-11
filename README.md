ImageTools for Windows Phone 8.1 (Not DEBUG mode!)
===============

ImageTools is a great free .NET library for rendering images.  It has long been a commonly used tool within the Windows Phone development community.  

The Windows Phone certification requirements were modified with the release of Windows Phone 8.1.  You may no longer submit an app using any assembly built in 'debug' mode.  Unfortunately, the only available version of ImageTools was built in 'debug' mode and the original developer has moved on from the project - never having released the source code!

I ran into this issue recently while submitting an update to my Windows Phone app, Nearby Live.  To workaround the problem, I modified the IL of the available version of ImageTools and removed the [Debuggable] attribute from the assembly.  This was sufficient for my app to pass through the Windows Phone Store certification process.

I am sure others are running into the same problem, so here are the patched assemblies.

Best,

Brian P. Hamachek
brian@brianhama.com