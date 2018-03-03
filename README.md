# web-page-assignment

## Customizing the Webpage
Open up two tabs in your browser, navigate to your webpage in one of the tabs and to your assignment repository in the other tab. Open up the ```index.html``` file for editing (make sure you use __soft wrap__ in the GitHub code editor to have linebreaks) in your browser and customize your web page in the following ways:

1. Change the line __This project is maintained by QEHSCS__ by replacing QEHSCS with your name.

Before continuing find and look closely at the HTML markup in the ```index.html``` file where the text of web page is included.. In particular notice the opening and closing  tags that are used to format the text, in particular the ```<h3>``` and ```</h3>```, ```<p>``` and ```</p>``` and ```<a href="...">``` and ```</a>``` tags.

You will now replace the default web page text with your own information.

2. Select a country of your choice 
3. Replace the title of the web page with the name of the country. Note that the title of the web page appears both in the tab and on top of the page.
4. Set up the following headings: Capital, Official Languages, Population Size, Land Area in Square Kilometers, Currency. Follwing each heading include the necessary text providing the indicated information. For example, under the heading Capital provide the name of the capital city of the country.
5. At the bottom of the web page include the following text __See Wikipedia for more information__ with the text linking to the corresponding Wikipedia page for the country.
6. Bonus Challenge: Add a picture of the country's flag to your web page.  

Before turning in your assignment make sure that the web page is formatted properly and nicely. Spelling mistakes, typos and ugly formatting will all result in deductions.

## Keeping up to date with the master repository
To keep your local assignment repository up to date with your teacher's repository you need follow the following procedure from the terminal (shell in Linux and Git Shell in the Windows GitHub client).

**Step 1:** The first time you are updating your repository you need to run the following command:
```
git remote add upstream https://github.com/mariopineda/CSE1210-assignment-1
```
**Step 2:** If you are using the same computer you do not have to do Step 1 in subsequent updates and you can skip right to Step 2. In this step you need to run the following two commands:
```
git fetch upstream
git merge upstream/master
```
**Step 3:** Resolve possible merge conflicts and commit.

**Step 5:** You local repository has now been updated using your teacher's master respository. Finally you need to push your local repository to GitHub to make sure that your GitHub repository is updated as well.

