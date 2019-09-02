## Steps to get the Python on Microcontrollers Newsletter from GitHub to Wordpress

Mike – September 2, 2019

1.	Go to the newsletter GitHub site drafts directory https://github.com/adafruit/circuitpython-weekly-newsletter/blob/gh-pages/_drafts/
2.	Rename the old newsletter from adafruit/circuitpython-weekly-newsletter/_drafts to ../_posts
3.	Download the assets for the current week to your PC
4.	Add the asset pictures to the Media section of the Wordpress site for adafruitdaily.com
5.	Go to https://adafruit.github.io/circuitpython-weekly-newsletter/ and open the latest newsletter
6.	Use browser “view source” and copy all the HTML from the title in h2 tags (just past <!-- main content-wrapping table -->) to and including the paragraph
> The CircuitPython Weekly Newsletter is a CircuitPython community-run newsletter emailed every Tuesday. The complete <a href="https://www.adafruitdaily.com/category/circuitpython/">archives are here</a>. It highlights the latest CircuitPython related news from around the web including Python and MicroPython developments. To contribute, edit next week’s draft <a href="https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts">on GitHub</a> and <a href="https://help.github.com/articles/editing-files-in-your-repository/">submit a pull request</a> with the changes. Join our <a href="https://adafru.it/discord">Discord</a> or <a href="https://forums.adafruit.com/viewforum.php?f=60">post to the forum</a> for any further questions.
7.	The trick is to take that text and replace some strings in it to change the image links from GitHub to Wordpress. For this I use notepad++ but many text editors have a search and replace function.
a.	Find the strings ../assets/09032019 (use the current date) and replace with 
https://cdn-daily-blog.adafruitdaily.com/uploads/2019/09 (09 is the current month)
b.	Replace all instances. There should be the same number of replaces as there are images in the newsletter.
8.	In the adafruitdaily.com wordpress https://www.adafruitdaily.com/wp/wp-admin/edit.php open a new post
9.	Name the post first as the title in the header text of the draft markdown followed by the social media tags: #Python #Adafruit #CircuitPython #PythonHardware @circuitpython @micropython @ThePSF @Adafruit
10.	Use the Text tab in the body box which allows entry of HTML rather than the regular text. 
11.	Paste in the HTML from notepad++ or wherever you did the string replace.
12.	Click the Visual tab and you should see the formatted newsletter with the pictures.
13.	If you don’t see the images, you have an image upload issue or the search/replace you used had an issue.
14.	Save a draft now
15.	Change the title to Heading 1.
16.	Go through the entire newsletter text doing the following:
a.	Edit any spelling, punctuation, and grammar issues.
b.	Ensure all hyperlinks appear correct
c.	If there is a place where a picture should be but isn’t (you’ll see text that indicates an issue), go into the HTML, look for the image file it wants, then go back into the assets for the newsletter and try to find the file. When found, add to the Media portion of Wordpress.
d.	Changes to check for:
i.	Circuit Python -> CircuitPython
ii.	CircuitPlayground -> Circuit Playground
iii.	Wifi -> WiFi
iv.	NeoPixel, DotStar, HalloWing, Bluetooth, etc. Use spellings on Adafruit.com website.
e.	All bulleted items need to have left justify added to the, (highlight and select left justify in the tools). This ensures they are not centered which looks crummy. This applies to the Libraries list. Phil sometimes uses bullets in the articles too.
f.	In the Events section, I usually add the country (and city of needed) to ensure International readers know where the event us. Pasadena, CA -> Pasadena, California, USA
17.	Save a draft again
18.	Change Categories from Uncategorized to Python for Microcontrollers
19.	Add tags: Newsletter, CircuitPython, MicroPython, Python
20.	Use the Preview button, upper right
21.	Read through once more, ensuring pictures, text, etc. all look ok. If there is something out of place, edit the text again.
22.	When done with the second review, save another draft
23.	Add the following “Read this email in your browser, click here!” in regular text at the top and the link text is the Permalink for this post just below the title in the editing window. PT added this recently to make it easier for email readers.
24.	In the upper right Publish box, click edit next to Publish immediately. Change to publish Tuesday at 07 00. Double check the date then click Publish.
25.	Ok, Newsletter complete.
26.	Get one of the previous emails I’ve sent out. Replace the links with the current links for the weeks’ newsletter.
a.	To circuit@adafruit.com
b.	Subject: Newsletter for September xx, 2019
c.	Here are the links for the Newsletter for September xx, 2019
d.	New link at top of post, the rest is all good.
e.	Wordpress (browser link):  https://www.adafruitdaily.com/wp/wp-admin/post.php?post=12102&action=edit&classic-editor
f.	WordPress Preview (link that Preview takes you to): https://www.adafruitdaily.com/?p=12102&preview=true
g.	The final URL (permalink link): https://www.adafruitdaily.com/2019/08/27/circuitpython-at-micro-center-micropython-takes-flight-with-feather-python-adafruit-circuitpython-pythonhardware-circuitpython-micropython-thepsf-adafruit/
h.	If you notice any issues, please feel free to fix it in Wordpress or email editor 
i.	GitHub: https://github.com/adafruit/circuitpython-weekly-newsletter/blob/gh-pages/_drafts/2019-08-27-draft.md
j.	Send
27.	Go back to the GitHub _drafts folder and copy all the markdown in template.md
28.	Create a new file 2019-09-xx-draft.md and copy in the template markdown and save.
29.	Copy the link to the new draft newsletter 
30.	BONUS! Create a new assets directory with the name 09xx2019 (you can add a README.md to keep the directory in GitHub. https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/assets. This has already been done for the 10th, 17th, and 24th.
