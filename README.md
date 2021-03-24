![ReDI](images/redi_banner.png)

### Intro to Computer Science - Basic knowledge of HTML

Mark completed tasks by inserting an X within the squared brackets [].

### Prepare your practice project

- [] Visit the origin github repository at https://github.com/ReDI-School/ber-intro-to-cs-2021-html-journal
- [] Fork the origin github repository at https://github.com/ReDI-School/ber-intro-to-cs-2021-html-journal. This will create your own personal copy of the origin repository.
- [] Copy the link of your fork. The link will look like https://github.com/your-github-username/ber-intro-to-cs-2021-html-journal.
- [] Open VsCode
- [] Click the `Explorer` icon of VsCode(the first icon to the left)
- [] Click on `Clone Repository`
- [] Paste the link of your fork and hit the `Enter` key on your keyboard
- [] Select a location on your computer where you want the files from the fork to be stored
- [] VsCode will ask you `Would you like to open the cloned repository?`. Click `Open in New Window`.

### Add HTML to display general journal information and clickable list of years

- [] Open `index.html`
- [] Add HTML markup to:
    - [] Display a page title for your journal
    - [] Display a header for your journal
    - [] Display an image for your journal
    - [] Display a list of clickable years (2020 and 2021)

### Add HTML to display general information for a year's journal entries and clickable list of months

- [] Open the 2020 Journal page `2020/index.html`
- [] Add HTML markup to:
    - [] Display a page title indicating the year
    - [] Display a header indicating the year
    - [] Display a list of clickable months in the year (December)
- [] Repeat the previous steps for 2021 in the `2021/index.html` file

### Add HTML to display general information for a month's journal entries and clickable list of days

- [] As an example, open the March 2021 Journal page `2021/march/index.html`
- [] Add HTML markup to:
    - [] Display a page title indicating the month and year
    - [] Display a header indicating the month and year
- [] Repeat the previous steps for all other months across your journal

### Add a single daily journal page in March 2021

- [] Go to the `2021/march` folder
- [] Create a new file 25.html
- [] Add HTML markup to:
    - [] Display a page title indicating 25th March 2021
    - [] Display a header indicating the day, month and year (25th March 2021)
    - [] Display an image you like
    - [] Display any journal text you like
- [] Go to the `2021/march/index.html` page 
- [] Add HTML markup to:
    - [] Display a link to the journal page for 25th march 2021 (`2021/march/25.html`)
 

### How to test your HTML Markup
- Click on the file in VsCode
- Right-click on the file and select `Copy Path`
- Open your browser
- Paste the path in the browser and press the `Enter` key on your keyboard
- You can update the file in VsCode and refresh the browser page to see the results of your updates

### Push (upload) your work to github
- From the VsCode menu bar, click on `Terminal`
- Click on `New Terminal`
- Run the following command to create a new branch
    - `git checkout -b my-html-work`
- Run the following command to prepare all the files to be uploaded to github
    - `git add .` (don't forget the "dot")
- Run the following commit the changes to the local git branch on your laptop
    - `git commit -a "my html file changes"`
- Run the following command to upload your local git branch to your github fork which is on the internet
    - `git push -u origin my-html-work`
- Open a Github pull request from your `my-html-work` branch to the main branch of your fork `main` or `master`
- Merge the pull request
- Victory!
    
