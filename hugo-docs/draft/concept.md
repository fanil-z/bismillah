---
date: 9 Apr 2022
author: fanil
draft: true

---

Concept
***********

	* A short title or a name: short description of the period.
	* :doc:`Islam Chronology <../chronology_main>`

>npm run build /production 
>npm run start /local serve
>npm update

updated npm packages and somehow fixed the bug with css not compiling.
cloudflare pages

## Description


maybe make the first post short.
yes


Hello everyone and Assalamu Aleikum, which means "peace be upon you". In our trying times and in any other time, let peace fill our hearts, our minds, and our dwellings.
I have gathered stories of prophets from the Quran, hadith, tafsir, a small portion of the Old Testament using various open sources and wrapped up my notes in a static website.
The website is build on Hugo and Hyas frameworks, pipelined and hosted on Render. Sources are written in Markdown.
Our prophet Muhammad ﷺ   said, "Seeking knowledge is an obligation upon every Muslim." I have had a good time trying to gather particles of an endless puzzle. It was good CSS/JS/Bootstrap practice. If God wills, I intend to continue and fix some bugs, finish the sections about death, the Apocalypse, and about what happens on the other side.
السلام عليكم ورحمة الله وبركاته

 after I learn to properly read the Quran.


 Abdallah teaches me to properly read the Quran.


--------------------------------------------------------------------------

scripts take up to 400KB

Hello everyone and Assalamu Aleikum, which means "peace be upon you". In our trying times and in any other time, let peace fill our hearts, our minds, and our dwellings.

When I started learning about Biblical and Islamic prophets 4-5 years ago, I had a hard time trying to figure out the historical order of stories from religious texts. Surahs of the Quran are not written in the chronological order. I was struggling to get the whole picture, so in order to combine different pieces together, I have wrapped up my notes about Islam into a static website. The main idea was to gather and currate stories of all prophets mentioned in the Quran and sahih hadith in one place and sort them according to a historical timeline. Along the way, I had to add additional historic events that are not mentioned in the Quran but that affected and shaped the world as we see today.

After testing several frameworks, I went forward with Hugo, which we also use  in MBition. Hugo is an extremely fast static HTML generator. It is open-source, flexible, has themes for user manuals and API references. Hugo can be a good candidate if you use Markdown and want to implement the docs-as-code concept in your documentation department.

The overall stack looks like this:

1. Hugo: a static web-site generator that builds a static HTML/CSS/JS website using MD files as a source. It is open-source, flexible; it has a large number of themes including themes for user manuals and API references. Hugo can be a good candidate if you use Markdown and want to implement the docs-as-code concept in your documentation department.
	- Hyas: I used the Hyas theme to have a good-looking bootstrap layout.
		- Hyas depends on Node.js and a swarm of npm packages. On Windows, you will also need Chocolatey to configure it.
		- Doks theme. I had to add and tune some JS/CSS elements to adjust the website to my purposes. Doks is a bit too advanced for a beginner like me so I still has plenty of bugs to fix. There are standard Hugo themes that can be configured in 5 min.
2. Render: I am hosting the website on Render. Up to 100GB bandwith and 400 total build hours is free of charge. I also tried Netlify, basically the same functionality.
3. A pipeline on Render fetches the latest commit in my git repo, installs all required npm packages, builds the website and pushes it to production. You can configure a test server on Render but I just test on my local machine.

The core structure of this guide is based on narrations of the Quran. Tafsir and verses are copied from various open sources.
 
> Other sources of this guide include: authentic hadiths, some non-authentic hadith, the Bible (Old Testament), some opinions of great islamic scholars of the past, a book by Karen Armstrong "Islam: A Short History", a book "Muhammad, His Biography Based on Earliest Sources". Some parts are derived from youtube lectures of sheikhs of our time (mostly Yasir Qadhi and Omar Suleiman). I tried to stick to aforementioned sources. Mostly it is copy-paste, I have gathered the information, currated it, combined together, and did some editing.

my notes on Yasir Qadhi's 114 lectures on seerah of the Prophet Muhammad SAW are scattered within corresponding sections. Some info is taken from Wikipedia, which is always helpful and well-structured. I tried to edit them, remove the parts that are not mentioned in The Quran or authentic hadiths, or parts that are too Shia. Also, I started to create summaries of some sections and reorganize them, but decided to publish it because I want to take a break and learn to properly read the Quran in Arabic.


Islam teaches to finish what you started and there are still many bugs and I have to finish the most interesting sections: Al Qiyamat--the Eshcatonian part, about death and what happens on the other side. 

I've spent 20-30 minutes a day for a year. Slowly it got into shape, Alhamdulillah. I had some good time trying to gather particles of an endless puzzle and intend to continue, if God wills.

Our prophet Muhammad ﷺ   said, "Seeking knowledge is an obligation upon every Muslim." and it amazes me how seeking knowledge became essential like drinking water for the first generation of Muslims, true ummah of Al Nabi ﷺ  . I envy my dear Egyptian brothers who study all this in madrasahs when they are young.

We do not appreciate enough that nowadays we can find data about any hadith, any historic event in seconds and listen to khutbas and lectures of best sheikhs from all over the world. That is truly a huge advantage and luxury that scholars of old times never had. Just read this hadith narrated by Jābir ibn Abdullah who travelled one month on a camel to listen to a one single hadith.

> It reached me that a man heard a Hadith from the Messenger of Allah ﷺ  , so I purchased a camel, then traveled quickly to him. I travelled for one month until I reached Sham.

The man was Abdullah ibn Unays. I said to the doorman, tell him Jābir is at the door. He replied, “Ibn Abdullah?” I said, “Yes.” He came out dragging his thobe. He hugged me and I hugged him.

I said to him, “It has reached me that there is a Hadith which you heard from the Messenger of Allah ﷺ   concerning the retribution. I was afraid that you might die, or I might die before I heard it.”

Abdullah ibn Unays then reports an interesting hadith, the full version of which is in the Day of Judgement section.

Peace and blessings be upon you

-----------------------------------------------------------------------------

Traveler: He is the noble companion Jābir ibn Abdullah ibn Amr ibn Harām. He narrated 1,540 Hadith. He fought in 19 battles alongside the Messenger of Allah ﷺ. His father was a companion. His seven sisters were all companions.

Narrator: He is the noble companion Abdullah ibn Unays. He prayed towards both Qiblas. He smashed the idols of Bani Salamah.

Abdullah ibn Unays said, “I heard the Messenger of Allah ﷺ  , ‘The people will be gathered on the Day of Standing—and he pointed with his hand towards Sham. They will be gathered naked, uncircumcised, and buhman.’ We said, ‘And what is buhman?’ He ﷺ   replied, ‘They will not have anything with them. Then a Caller will call out with a voice heard equally by those far and near (saying), ‘I am the King, I am the Reckoner. It is not befitting that anyone from the inhabitants of the Hellfire should enter the Hellfire while someone from the inhabitants of Paradise owes him a right, until he settles it. And it is not befitting that anyone from the inhabitants of Paradise enters Paradise while someone from the inhabitants of the Hellfire owes him a right, until he settles it, even if it is only a slap.’’ We said, ‘And how will this be, when we will stand before Allah, naked, uncircumcised, without anything?’ He ﷺ   replied, ‘With good deeds and bad deeds.’” (Al-Adab Al-Mufrad, #970, declared Hasan by al-Albani)

it is build on the Hugo framework with Hyas

I started wrapping up my notes about Islam into a static website and after one year of spending 20-30 minutes daily, the MD editor showed it would take 12 hours to read the whole thing.


gathered from various web resources:
Islam: A Short History by Karen Armstrong who is a famous historian and a Christian nun.


and logic behind the selected layout

Another aspect that always bothers me in large documentation samples is that it is not easy to create a proper helicopter view of the whole thing. TOC helps you to navigate but doesn't give a summary. However in terms of historical texts, TOC can actually provide a short description of what happened in the correct order. 

At first, I wanted to combine the guide from interlinked separate parts where each definition can be source for its own wiki page. hugo has functionality for snippets but seemed like it would require one-level-higher content planning and too much overhead so I chose the simplest way.

Trying to combine the helicopter view and large portions of text, I've used the standard <details><summary> tags so that details about a historic event appears when you click on the topic.




The overall stack looks like this:
1. Hugo: a static web-site generator builds a static HTML/CSS/JS website using MD files as a source.
	- Hyas: I used the Hyas theme to have a good-looking, neat bootstrap layout.
		- Hyas depends on Node.js. I installed it on my laptop.
		  Node.js is easy to install on Linux and probably Mac. On Windows, you will need Chocolatey.
	- Doks theme
		- CSS: The theme is neat but I needed to adjust it to my purposes. So, I added the custom CSS file (~150 lines).
		- JS: added buttons for sending feedback, expanding/hiding details elements all at once, in-page search and dark mode switch toggle.
		- Hugo is super-flexible and has a large amount of useful features but at the beginning it was hard to navigate through all the functionality and figure out which exactly config files I had to change. Hugo documentation is helpful here. 
2. Render or Netlify: static web-files are hosted on Render. up to 100GB bandwisth a month is free. And 400 total build hours per month for free services and static sites.
3. A pipeline on Render automatically fetches my latest commit in the git repo, installs all required npm packages, builds the website and pushes it to production. You can configure a test server on Render but I just test on my local machine.


I bought the domain here:
4. 
5. Markdown: the content is written in Markdown files + with some HTML additions.
6. GitLab: source files for content + CSS, JS, themes are stored in GitLab.


btw last year I realized that my father's name Gilmetdeen means "Knowledge of the religion" in Arabic. It is an old Tatar name; I couldn't think of another domain so I bought it.

Hugo has good documentation, but custom themes mostly written by front-end enthusiasts almost don't have documentation, which leaves you to reverse engineer the setup. I wouldn't recommend Hyas/Doks for beginners or if you want to customize the layout or CSS, there are much simpler themes of Hugo that can be configured in 5 min.



Please send your feedback to islam-wiki@proton.me if the order is not correct or if you find something conradicting the Quran or authentic hadith.

Probably I wouldn't be able to finish the the website if the content was not about Islam which is exciting to explore. However the most painful part was to gather information on the First Fitnah and how the era of righteous khalifs came to an end after assassination of Ali. Even though the Golden Age of Islam starts right after, for me it is the saddest periods of Islamic history, when we can say that the original ummah of the Prophet Muhammad ceased to exist. May Allah forgive us and guide us to the right path.

I also had to spend additional time adding a cat 🐈 every time the name of the noble Abu Huraira ("Father of a kitten") comes up. Was totally worth it.


, verily, Abu Huraira stands for "Father of a kitten" in Arabic. Was totally worth it and I do not consider it as israf of time.

After realizing that you can do so many things without a web server but just with HTML, CSS and JavaScript, I really started to like the simplicity of what's happening behind the building and hosting process.
Well, maybe the fact that I know very little about building a web server plays a significant role here as well.

I really need to finish the Eschatonian part, for now it's hard to figure out the order of events in the signs of Day of Judgement and Al Qiyamah itself. So the section has the [TBD] tag. Actually, The Apocalypse and jinns (spirits and devils) are two topics that I find the most interest among non-Muslim people as well.



The main page markdown file is 8000 lines. Islam teaches to finish what you started, so I tried to spend on this at least 20 minutes a day. Slowly it got into shape, Alhamdulillah. I had some good time trying to gather particles of an endless puzzle.
but there are still many bugs left.
I have many doubts like was Thamud earlier than 'Ad or vice versa.

hugo is a good choice if you want to implement docs-as-code approach and if the documentation team is ready to work with markdown instead of traditional XML editors.
I've been editing raw markdown files for a while until I found about https://github.com/marktext/marktext which is open source and really nice. has a spell checker.

https://github.com/mundimark/awesome-markdown-editors

90k words, 6000 paragraphs.
My Ghostwriter editor says the reading time of the whole thing is 6 hours. I wonder how much time I've spent there.

I need to relisten some lectures from Seerah of prophet Muhammad SAW and finish the History of Islam section.

https://miro.com/app/board/o9J_kqBzhXk=/
https://docs.gitbook.com



Published on Render: https://islam-wiki.onrender.com/docs/wiki/islam-wiki

Anas ibn Malik reported that prophet Muhammad ﷺ   said, "Seeking knowledge is an obligation upon every Muslim." 

and you can see the evidence of how seeking knowledge became essential like drinking water for the first generation of Muslims.
I envy my dear Egyptian friends who study all this in madrasahs when they are young.

We do not appreciate enough how amazing is that nowadays we can find data about any historic event in seconds just sitting on a chair and listen to khutbas and lectures of best sheikhs from any country. That is truly a huge advantage and luxury that scholars of old times never had. Just remember the scholar who had to travel on foot and camels all the way up to Basra in order just to listen for one single hadith because his teacher said that some years ago he heard a man from Basra reporting this hadith. 


### Note on CSS

THe website wouldn't get the bootstrap css from @hyas node on production builds. I don't know how to fix it, so I just implemented added an additional custom CSS file in the head.html. Using this approach I can actually just use a simple hugo theme and bump the CSS there. I don't know. 

### On this page
[tableOfContents]
  endLevel = 4
  ordered = false
  startLevel = 1

config/smarkup.html


### Disabling TOC

---
toc: false

---
in the front matter of the page.

https://www.printmag.com/categories/print-awards/
https://nowthisnews.com

# NEXT STEPS

1. Generate arts using Stable Diffusion. 

https://www.howtogeek.com/830179/how-to-run-stable-diffusion-on-your-pc-to-generate-ai-images/

Requirements:
* All pics must be in one style.
* Maybe pixelart.

2. Recently I became a fan of [The Pudding](https://pudding.cool) and how they play with CSS and JS to create interactive data visuals like for example [this article about Aztec mythology](https://pudding.cool/2022/06/aztec-gods/).

3. Reduce the size of the website to 1,5MB.
https://habr.com/ru/company/ruvds/blog/692840/
My friend sent me this blog post about how people make 14KB websites and 56byte stylesheets, and I realized that 2 png images are occupying 91% of my network traffic. It helped me to reduce the weight from 10MB to 2,2MB, which might actually help me remain inside kosten-frei 100GB per month limit in Render.
	* remove unused css.
	* buttons and scripts.

4. Add timeline.





[OLD] I have some thoughts on how to make it user-friendly for mobile users. probably this will require some changes in the H1 structure. For example, we can put the H1 child content inside the details tag and then hide all the content. so that mobile users will se only the H1 headers and they will need to click the header to expand its child H2 headers. This will make it minimalistic and more interactive.

Also, we can remove te on this page section at all as it is useless anyway. instead we can add a button for different depths. For example, show only H1 headers, show h1 & h2 headers, and expand all.


Need to do
===========
## STAGE 1. World History Map (General) 
***************************

1. [DONE] Come up with the concept. Some algorithm to make it convenient to read and to support.
	* [DONE] maybe just switch to Hugo as it seems more convenient and versatile:
		* hugo-doks +
		* hugo-book
		* hugo-learn
		* A bad thing about choosing a custom theme is that it may end up not supporting some of the functions that you need and you will learn about it very late in the game and it will be too troublesome to change to some other theme. Also, hugo has documentation, but the themes which in most cases have a bunch of their own code and functions have a very general-level docuentation. I guess mostly because the themes were created by volunteering front-end developers and not by technical writers. that's why these things are smart and dynamic but without instructions.
2. Copy-paste topics.
3. Fact-check and rewrite the topics. 
4. - Buy a hosting place. Just upload to Render.
5. Buy a domain.
5. [DONE] add some images or emoji
6. [DON-] write a disclaimer


## STAGE 2. World History Map (Technical Tasks)

* Need index-numbers and maybe certain div classes for titles and descriptions.
* Send Feedback button
* add favicon
* [DONE] add head menu with links
* [DONE] add custom css
* find how to build a static website with config
	seems like I need to upload it somewhere and fix the baseurl in config before it starts to work locally without serve.
* [DONE] find a way to deal with bootstrap CSS
* [DONE] deal with the TOC (how did I do that?)
* [DONE] attach the upper panel (position: sticky)
* [DONE] expand all toggle (https://stackoverflow.com/questions/43008609/expanding-all-details-tags)
	* Maybe also make this a switch-toggle instead of a button.
* dark mode toggle slider: https://infomate.club/howtoberlin/
* sticky panel include: dark mode toggle, expand all toggle, back to Home link, ?search, ?git link
* change the upper line gradient color
* add a timeline since Ibrahim. now there's no way I can hack bootstrap css on that level
* [DONE] fix CSS for This-Page-TOC background and border in the bootstrap CSS.
* add button to go up to the beginning: 
* [DONE] incorporate search in the current page: https://stackoverflow.com/questions/51988459/html-searching-on-the-same-page/51988637
* put search button inside search field
* -- Try GitLab Pages. Seems like it's free compared to GitHub Pages. (Free but you need to provide your CC data.)
* Do Expand All when clicking a section in the TOC
* [DONE] Create a mockup for timeline-helicopter view of the seerah of Prophet Muhammad sww.


Dark mode switch: https://dev.to/ahmadbassamemran/awesome-animation-checkbox-css-toggle-day-night-mode-5dnm




### Other Stuff
* https://www.islam-guide.com/truth.htm maybe contact them and fix their CSS.
* add the "Useful Links" section


## Notes
* **expand all** script is in layout/docs/single.html
* the menu, buttons, Expand All in the layout/partials/header/header.html
* To fix CSS, use files from the /scss/common directory.
seems like my sense of beauty is inevitably falling behind my willingness to fix all CSS issues.



border-image-source: linear-gradient(
89deg, #067f11e3, #05ffcab3 50%, #4fe622ab);

<label class="switch">
  <input type="checkbox">
  <span class="slider round"></span>
</label>


JS scripts are in single.html. Need to transform them to separate scripts in the js folder.




Sections
===========
1. Ultimate Roadmap of the Universe According to Islam
2. Seerah of the Prophet Muhammad sww with timeline-helicopter view (REST API documentation style) 
2. Interactive chart with the Prophets family.
3. Islam and Science (Scientific Miracles of the Quran)
4. Synopsis for each episode of the seerah of the prophet Muhammad saw
5. Comparison with other religions
6. [God's creation compared to computer programming]
7. Maybe make the interactive chart of connections like in Infinite Jest.
8. Interactive diagram of how persons good and bad deeds are collected by angels and sent to Jannah and Jahannam where they obtain some form.
9. amazingness of how first generations of Muslim scholars collected hadith and.


Custom Header
****************************
* Tabs: 
	* History Map
	* Home
	* Other Stuff
	* Contacts

Databases
****************************
* Prophets
* Sahabi and other important people
* Hadith
* Quran Surahs

An interactive family tree of prophets.
****************************
*  just CSS and HTML: https://codepen.io/Pestov/pen/BLpgm


Nice to Have
****************************


## Hosting

Deploy your static site easily on Render.

Just Link GitLab or GitHub repository, and let it build your website and serve it on a global CDN. The best thing is that static sites are free on Render with no additional cost of up to 100 GB bandwidth a month.