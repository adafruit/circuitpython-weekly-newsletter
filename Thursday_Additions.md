## Thursday Additions

**This information should be added by Thursday afternoon at the latest! It can be done on Wednesday
if needed.**

This is the workflow for adding certain parts of the newsletter on Wednesday or Thursday afternoons.

### Here are the URLs used for adding the Wed/Thu bits to the newsletter:
- https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_drafts
- https://github.com/adafruit/circuitpython-weekly-newsletter/tree/gh-pages/_posts
- https://learn.adafruit.com/guides/latest
- https://github.com/adafruit/Adafruit_CircuitPython_Bundle/blob/main/circuitpython_library_list.md
- https://raw.githubusercontent.com/adafruit/CircuitPython_Community_Bundle/main/.gitmodules
- https://adafruit-circuit-python.s3.amazonaws.com/index.html?prefix=adabot/bin/reports/
- https://github.com/adafruit/circuitpython/releases
- https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases
- https://github.com/adafruit/CircuitPython_Community_Bundle/releases
- https://micropython.org/download
- https://www.python.org/downloads/
- https://www.python.org/download/pre-releases/
- https://github.com/adafruit/circuitpython/stargazers

### Open the current and previous newsletters:
- Open up the current draft in a tab. (From /_drafts)
- Open the most recent published newsletter in a separate tab. (From /_.posts)

### Add new Learn Guides:
- Scroll down to the Learn guides in the most recent published newsletter.
- Go to the Latest guides on Learn, determine where I left off from last week by looking at the most recently published newsletter. Then open all the new CircuitPython-related guides in tabs. (Sometimes I have to open a guide and check if it’s CP or not.)
- In the newsletter draft, scroll to “New Learn Guides!”
- Below the title is the format for including new Learn guides. Get the appropriate info from each page to include on one line per guide in the newsletter. (See past newsletters if you need clarification.)
- You may need to add more lines for more guides, or remove some of the templated lines if there are less.

### Update the Libraries Section:
- Update the number of libraries:
  - Check the CircuitPython Library List in the Bundle repo to get the current number of Adafruit CircuitPython libraries. It is listed under the picture of Blinka.
  - Go to the CircuitPython Community Bundle tab, and do a Find In Page (cmd+f, ctrl+f, or whatever fits the machine you’re using) for “submodule”, and it will provide you with a “number of matches”. 
  - Add the number of Adafruit CircuitPython libraries from the Adafruit Bundle CircuitPython Library List page to the number of submodules on the Community Bundle .gitmodules page.
  - Put that combined total number into the CircuitPython Libraries section of the newsletter draft. It is represented by `###` between two sets of `**`. Replace the `###` with the total library number.
- Update the library section info:
  - In the S3 AWS bucket tab, click on the latest circuitpython_library_support_YYYYMMDD.txt link.
  - From the CircuitPython report page, scroll down to “Library updates in the last seven days”. 
  - Copy the bullet list from under the **New Libraries** header.
  - Paste that into the CircuitPython Libraries! section of the newsletter under “New libraries!” 
  - If there are no new libraries, delete the "New libraries!" Header and the blurb below it from the newsletter.
  - Go back to the CircuitPython report page, scroll down to “Library updates in the last seven days”. 
  - Copy the bullet list from under the **Updated Libraries** header.
  - Paste that into the CircuitPython Libraries! section of the newsletter under “Updated libraries!”
  - If there are no updated libraries, delete the "Updated libraries!" Header and the blurb below it.
  - If there are no new or updated libraries, delete bothm and include a sentence saying, "There are no library updates for this week. Check back next week for more!"
- Update the Library PyPI Download stats info:
  - Go back to the CircuitPython report page. Copy everything under the "Library PyPI Weekly Download Stats" header, from the first `*` to the final download number.
  - Paste it into the Libraries section under "Library PyPI Weekly Download Stats" header.

### Update the Latest Releases section:
- Scroll down to the Latest Releases section in the newsletter draft.
- Use the rest of the open tabs to enter the appropriate information into this section. Follow the format of the template. The info available in the tabs fits the template.
- When entering the number of Stargazers, please include a `,` in the number, e.g, `3,456`, 
- Note! Sometimes CircuitPython and Python do not have unstable releases. In that event, delete that part of the sentence, and only include the stable release.

Commit, and submit a PR to the circuitpython-weekly-newsletter repo, tagging @thekitty as a reviewer. 
Notify Anne on Slack as well.

Update 2023-09-13 by Kattni
