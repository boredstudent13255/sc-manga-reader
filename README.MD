<h2>SierraComix Manga Reader</h2>

This readme will just be documentation for various end user features.

<h3>Query tags for reader.html</h3>

<b>"s"</b> - specifies the series ID to load from. <br>
's=chou-kuse' to load a chou kuse chapter

<b>"c"</b> - Specifies the target chapter. <br>
'c=10' to load the tenth chapter

<b>"p"</b> - Specifies a page number to jump to on load. <br>
'p=12' or 'p=11' will both direct the user to the screen containing pages 11 and 12.

<b>"bg"</b> - Allows for setting a custom background color using a standard hex color code. NOTE: This tag will not carry over between chapters. It's mainly intended for use in conjunction with the "embed" tag. <br>
'bg=FFFFFF' will set the background color to white.

<b>"embed"</b> - Disables changing chapters and forcibly hides the on-screen controls. Intended to be used for embedding a single chapter on another website. <br>
'embed=true' enabled embed mode.

<b>"d"</b> - Specifies the target domain. <br>
'd=https://boredstudent13255.github.io/sc-manga-reader/test-entry/' will fetch the specified series from my test entry, a technically different domain. In nav-chapter, if the series is set to 'test-series', it will display that test series entry and its test chapter entry. <br>
So long as a series is hosted in the proper format, with the required "series.xml" and "chapter.xml"s in place, this query tag enables this reader to access manga from anywhere on the internet. <br>
This feature is a sort of prototype for Nagisa Reader, which is better explained by the (currently empty) repo on my profile.