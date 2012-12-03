### Hong Kong Coders Open Directory

- open data set hosted on github, that eveyone can read and fork
- consolidate Hong Kong coders information and try to determine how does a Hong Kong coder may look like

### What to do with these data

- develop applications or visualizations about coders and about the coding communities
e.g. job board, skill matching, project formation
- conduct some (weird) researches
e.g.
  "How many windows developers you need to change a light bulb ?"
  "Which group contribute more open source projects ? Windows users or Mac users ?"  
  "Which group like curly braces ? Rubyists or Pythonists ?",
  "Which group like staying in the same company for longer time ?"  

### Who owns the data ?

- We will keep this repository public to everyone
- Codeaholics HK organizers will help maintaining the master branch (feel free to fork and send us Pull Request)
- You can fork it and maintain your own data set too

### Data Structure Design Guidelines

- data should be timeless, e.g. specify when did you start coding instead of saying how long had you been coding for.
- to avoid duplicated maintenance effort, if there is some data about the user or the meetup that already exist somewhere else, include the url in the data, but not copy and paste the content into another json file.
- consider using column based data set, if you are expecting a lots of aggregation for that data set, e.g.