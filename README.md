# code-heimer
Hackathon project for Scientific software corpus using using WoC Data and AI/LLM

### Team members: 
- Addi Malviya-Thakur
- Reed Milewicz
- Ahmed Samir Imam Mahmoud
- Lavinia Pagnini
- Sean Kwak
- Kyungchan Lim


### Todos:
How do we define scientific software?

How do we filter all projects in world of code

  -start with attributes in mongo

  -come up with criteria and supporting evidence  (97295 projects)
  
  ```
  db.P_metadata.V.findOne({ 
        $where: function() { return this.NumFiles > this.FileInfo.other }, 
        NumFiles: { $gt: 5 }, 
        NumCommits: { $gt: 500 }, 
        NumAuthors: { $gt: 5 }, 
        NumActiveMon: { $gt: 6 },	
        LatestCommitDate: { $gt: 1542572838 }})
  ```
Once we have a list of filtered projects, obtain their readme md files

Compile a dataset of projects, urls and their readme.mds

Work on the llm prompts and the desired output format that is parse friendly 

Run the readme.md code through LLM prompts

parse the output data into the dataset

Iteratively validate the results from above 

Once we have the dataset, use sampling for data quality 



Use case demonstrations: 

DEI: Laviginia, could you please some text

Security: Use CodeQL to scan vulnerability from OSS.
- Check if CodeQL can be run with only repository information (name or link)
- After getting scientific code extracted from WoC, we can run CodeQL to check for vulnerabilities.
