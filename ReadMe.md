# Extra People Icons

Ever wanted some extra "people" icons for your Sitecore instances? Cartoons of MVPs? St Arnold (<a href="https://www.saintarnold.com/year-round-beers/#lawnmower">of lawnmower fame</a>)? The Sitecore Pillow? Bobby Hack? Well, now you can...

<img src="Icons.png" />

## Installing

For the moment, it's not automated. To add these files to an instance of Sitecore you need to:

1. Grab a copy of the "`<size>x<size>`" folders under the "`People`" folder in the repo above.
2. Find "`People.zip`" in your "`<instance>\Website\sitecore\shell\Themes\Standard`" folder and open it.<br/>(You may wish to back this file up before you change anything)
3. Paste the new folders into that zip, so that they add to the similarly named existing folders that are in it already.
4. Delete the "`<instance>\Website\temp\icons_People.*`" files, if they exist.
5. You may also need to delete anything in your "`<instance>\Website\temp\IconCache`" folder if it exists.

And then when you go to the "Set Icon" dialog in Content Editor, you should see the new Icons in the People section. (They work for user account icons too, but you'll have to paste the icon's path into the user editor's field, as that doesn't allow picking from the People collection)

Remember that you'll need to deploy these icons to any other platforms you deploy your site too.

----

Original artwork for the MVPs came from <a href="http://www.digitalcaricatureslive.com">Digital Caricatures Live</a>. If they work in your neck of the woods, hire them for your next event!

----

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.