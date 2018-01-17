# olefine.eu

This is the public website of the H2020 project OLEFINE (OLEAginous yeast platforms for FINE chemicals) funded by the European Commision.

## Modifying the website on GitHub (for non-experts)

Once you opened a file in GitHub (click on it), you can edit it by clicking on the pen icon in the upper right corner. After you're done with your changes, scroll to the bottom of the page and click on 'Commit changes'. 

### News

News items can be found under [_posts](_posts) written in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) an extremely simple plain-text language for writing content. You can add a news item by creating a file under [_posts](_posts) (click on the 'Create new file' button) and giving it a name that starts with the publication date (e.g. 2018-01-16) and ends with the title of the news item (e.g. 'Kick-off-meeting' use hyphens instead of spaces) resulting in '2018-01-16-Kick-off-meeting' ([_posts](_posts) also contains an example file). The content of the news items starts with a header section:

    ---
    layout: post
    title: Kick-off meeting
    published: false
    ---
You can set `published` to `true` or `false` in order to add or remove it from the website. After the header section you put the content of the news item. For example,

	The official kick-off meeting of the DD-DeCaF project was held in Brussels on 7-8 March 2016 at [creoDK](https://www.regionh.dk/creodk/Sider/default.aspx) and hosted by the project coordinator the Novo Nordisk Foundation Center for Biosustainability.
	Representatives from all the different partners were present to officially start up the project and discuss the project’s management and implementation plan, work packages and tasks. It was also discussed outreach, communication and exploitation issues and technological details that will be addressed under the scope of DD-DeCaF.
	Mr Ioannis Vouldis, project officer of the European Commission (EC), was also present at this meeting where he presented an introduction to [Horizon2020](https://ec.europa.eu/programmes/horizon2020/) and its best practices.
	The next consortium meeting will be held at Heildelberg (Germany) on 26-27 September 2016 and hosted by [EMBL](http://www.embl.de/).
	![description of the image for the blind](/images/photo_kick-off_meeting.jpg)
  
If you want to include an image in your news item, please upload it first to [images](images) (click on the 'Upload files' button in the upper right corner after navigating to [images](images)) or click [here](https://github.com/biosustain/olefine-website/upload/master/images).

### Other content

The different sections (Banner, News, Consortium, etc.) of the website can be found under [_includes](_includes) (they are written in HTML).

## Local development (for experts)

Need to run `jspm install` before `jekyl serve` to serve site locally.
Need to run `sass --watch sass:css --style nested` to generate CSS.
