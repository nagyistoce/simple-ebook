Author:
> Moky


Date:
> 2011/05/04


HOWTO:

  1. Create a new project,
> > select 'View-based Application';


> 2. Right click 'Frameworks',
> > select 'Add' -> 'Existing Frameworks',
> > import 'AVFoundation.framework' and 'QuartzCore.framework';


> 3. Right click 'Classes',
> > select 'Add' -> 'Existing Files',
> > import the 4 files in the 'include' directory;
> > Modify your new 'XxxViewController.h' and 'XxxViewController.m'
> > (actually, just simply copy the codes from the 'sample' into them);


> 4. Right click 'Resources',
> > select 'Add' -> 'Existing Files',
> > import the mp3 and png files in the 'res' directory;


> 5. Import the files in the 'data' directory into 'Resources',
> > all modification will be under this directory from now on;
> > You can add new slices with images and sounds,
> > don't forget to do the relative modifying in 'Config.plist'.