## Friday Additions

This is the workflow for adding certain parts of the newsletter on Friday afternoons:

Here are the URLs used for adding the Friday bits to the newsletter:
- https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts
- https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_posts
- https://learn.adafruit.com/guides/latest
- https://github.com/adafruit/Adafruit_CircuitPython_Bundle/blob/master/circuitpython_library_list.md
- https://github.com/adafruit/CircuitPython_Community_Bundle/blob/master/.gitmodules
- https://github.com/adafruit/circuitpython/stargazers
- https://adafruit-circuit-python.s3.amazonaws.com/index.html?prefix=adabot/bin/reports/

Order in which to do things:
- Open up the current draft. (From /_drafts)
- Open the most recent published newsletter. (From /_.posts)
- Scroll down to the Learn guides in the most recent published newsletter.
- Go to the Latest guides on Learn, determine where I left off from last week by looking at the most recently published newsletter. Then open all the new CircuitPython-related guides in tabs. (Sometimes I have to open a guide and check if it’s CP or not.)
- Check the CircuitPython Library List in the Bundle repo to get the current number of Adafruit CircuitPython libraries. 
- Go to the CircuitPython Community Bundle tab, and do a Find In Page (ctrl+f or whatever fits the machine you’re using) for “submodule”, and it should provide you with a “number of matches” (currently 28). 
- Add the number of Adafruit CircuitPython libraries from the Adafruit Bundle page to the number of submodules on the Community Bundle page.
- Put that combined number into the CircuitPython Libraries section of the newsletter draft.
- Check the Stargazers tab for the total number of CircuitPython stars, and add that at the bottom of the “Latest Releases” section in the newsletter draft.
- In the S3 AWS bucket tab, click on the latest circuitpython_library_support_YYYYMMDD.txt link.
- From the CircuitPython report page, scroll down to “Library updates in the last seven days”. Copy the bullet list from under the **New Libraries** header.
- Paste that into the CircuitPython Libraries! section of the newsletter under “New libraries!” 
- If there are no new libraries, delete the “New libraries!" Header and the blurb below it from the newsletter.
- Go back to the CircuitPython report page, scroll down to “Library updates in the last seven days”. Copy the bullet list from under the **Updated Libraries** header.
- Paste that into the CircuitPython Libraries! section of the newsletter under “Updated libraries!” 
- In the newsletter draft, scroll up to “New Learn Guides!”
- Below it is the format for including new Learn guides. You’ll go through the tabs you opened in step 4. And get the appropriate info from each page to include on one line per guide in the newsletter. (See past newsletters if you need clarification.)

Push to master, and you’re done. Hopefully this is clear enough.

Update 2020-09-11 by Kattni
