---
layout: default
---

# Project HIGH-VAE

> A general variational autoencoder framework aimed at fitting high-cardinality & heterogenous tabular data.
  
  
  


* * *    


## Project Resources:

*   [High-VAE General Project Description](https://kod5kod.github.io/PhDev/pages/HighVAE_general.pdf)
*   [Project's Kanban Board](https://github.com/kod5kod/HighVAE/projects/1)
      

## Colab Notebooks:




* * *  


## Project Roadmap


### Research Stages

__(A) Basic exploration:__  
* Identify competition/current state-of-the-art approches     
* Why current approaches don't work well on our data of interest (specific examples)  
* Specify our proposals to combat shortcomings of current approaches (entity embeddings)   
* Identify/Gather datasets   
* Identify evaluation methods/metrics  
  
__(B) Proof of concept (PoC)__   
* Develop an entity-embedding VAE architecture  
* Test on high-cardinality datasets using evaluation method of choice
* Test against one-hot encoding  
* Test against top 2-current approaches
* Evaluate embeddings 
  
__(C) Evaluate PoC on various datasets__     
* Test on various datasets with different characteristics  
* Test on more current approaches 
* Test using more evaluation methods
* Identify strengths and weaknesses  
  
__(D) Test and deploy improvements (another R&D cycle)__  
* Research improvements/additions to the methodology  
* Add improvements into the code
* Test and benchmark again against current approaches
  
__(E) Develop a general python framework__    
* Develop a general python pipeline for learning high-cardinality & heterogenous data using VAE  
* Create a user-friendly library for synthetic data generation & embeddings visualization   
* Push to github
  
__(F) Provide an evaluation framework__       
* Develop a general evaluation framework of different approaches using different datasets and evaluation metrics
* Create a user-friendly library for evaluating different methods & datasets 
* Push to github
  
__(G) Upload paper to arxive__   
* Finalize paper write-up  
* Finalize and make the code/repository public  

### Research Schedule by Week

<style type="text/css">
.tg  {border:none;border-collapse:collapse;border-color:#aaa;border-spacing:0;}
.tg td{background-color:#fff;border-color:#aaa;border-style:solid;border-width:0px;color:#333;
  font-family:Arial, sans-serif;font-size:14px;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{background-color:#f38630;border-color:#aaa;border-style:solid;border-width:0px;color:#fff;
  font-family:Arial, sans-serif;font-size:14px;font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-7p3h{border-color:inherit;font-size:x-small;text-align:left;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-g7sd{border-color:inherit;font-weight:bold;text-align:left;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">Week</th>
    <th class="tg-0pky">Starts</th>
    <th class="tg-0pky">Ends</th>
    <th class="tg-0pky">Stage</th>
    <th class="tg-0pky">Theory&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.</th>
    <th class="tg-0pky">Development&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.</th>
    <th class="tg-0pky">Writing&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.</th>
    <th class="tg-0pky">Limitations&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.<br><br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 19</span></td>
    <td class="tg-0pky">Sunday, May 8</td>
    <td class="tg-0pky">Saturday, May 14</td>
    <td class="tg-0pky">Basic exploration</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Identify datasets<br>&nbsp;&nbsp;<br></td>
    <td class="tg-7p3h">identify current approaches</td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 20</span></td>
    <td class="tg-0pky">Sunday, May 15</td>
    <td class="tg-0pky">Saturday, May 21</td>
    <td class="tg-0pky">Basic exploration</td>
    <td class="tg-7p3h">identify current approaches<br>Identify drawbacks of approaches</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Identify drawbacks of approaches<br>Specify our proposal</td>
    <td class="tg-7p3h">52002 midterms</td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 21</span></td>
    <td class="tg-0pky">Sunday, May 22</td>
    <td class="tg-0pky">Saturday, May 28</td>
    <td class="tg-0pky">Proof of concept</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Develop an entity-embedding VAE<br>Test on high-cardinality datasets<br>Test against one-hot encoding</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 22</span></td>
    <td class="tg-0pky">Sunday, May 29</td>
    <td class="tg-0pky">Saturday, June 4</td>
    <td class="tg-0pky">Proof of concept</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"><br>Deploy current approaches on my env.<br></td>
    <td class="tg-7p3h">Provide high level structure of paper</td>
    <td class="tg-7p3h">Shavout</td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 23</span></td>
    <td class="tg-0pky">Sunday, June 5</td>
    <td class="tg-0pky">Saturday, June 11</td>
    <td class="tg-0pky">Proof of concept</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Test against top 2-current approaches<br>Evaluate embeddings</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 24</span></td>
    <td class="tg-0pky">Sunday, June 12</td>
    <td class="tg-0pky">Saturday, June 18</td>
    <td class="tg-0pky">Evaluate on various datasets</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Test on various datasetsTest on more current approaches</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 25</span></td>
    <td class="tg-0pky">Sunday, June 19</td>
    <td class="tg-0pky">Saturday, June 25</td>
    <td class="tg-0pky">Evaluate on various datasets</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Test using more evaluation methods<br>Identify strengths and weaknesses<br></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 26</span></td>
    <td class="tg-0pky">Sunday, June 26</td>
    <td class="tg-0pky">Saturday, July 2</td>
    <td class="tg-0pky">Test and deploy improvements</td>
    <td class="tg-7p3h">Research improvements/additions</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 27</span></td>
    <td class="tg-0pky">Sunday, July 3</td>
    <td class="tg-0pky">Saturday, July 9</td>
    <td class="tg-0pky">Test and deploy improvements</td>
    <td class="tg-7p3h">Research improvements/additions</td>
    <td class="tg-7p3h">Add improvements into the code<br>Test and benchmark again against current approaches<br></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 28</span></td>
    <td class="tg-0pky">Sunday, July 10</td>
    <td class="tg-0pky">Saturday, July 16</td>
    <td class="tg-0pky">Test and deploy improvements</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Add improvements into the code<br>Test and benchmark again against current approaches<br></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 29</span></td>
    <td class="tg-0pky">Sunday, July 17</td>
    <td class="tg-0pky">Saturday, July 23</td>
    <td class="tg-0pky">Develop a python framework</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Develop a general python pipeline</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 30</span></td>
    <td class="tg-0pky">Sunday, July 24</td>
    <td class="tg-0pky">Saturday, July 30</td>
    <td class="tg-0pky">Develop a python framework</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Develop a general python pipeline<br>Create python library<br></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 31</span></td>
    <td class="tg-0pky">Sunday, July 31</td>
    <td class="tg-0pky">Saturday, August 6</td>
    <td class="tg-0pky">Develop a python framework</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Test pipeline on different conditions/datasets</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 32</span></td>
    <td class="tg-0pky">Sunday, August 7</td>
    <td class="tg-0pky">Saturday, August 13</td>
    <td class="tg-0pky">Debt payback week</td>
    <td class="tg-7p3h">TBD</td>
    <td class="tg-7p3h">TBD</td>
    <td class="tg-7p3h">TBD</td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 33</span></td>
    <td class="tg-0pky">Sunday, August 14</td>
    <td class="tg-0pky">Saturday, August 20</td>
    <td class="tg-0pky"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Vacation</td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 34</span></td>
    <td class="tg-0pky">Sunday, August 21</td>
    <td class="tg-0pky">Saturday, August 27</td>
    <td class="tg-0pky">Evaluation framework</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Develop a general evaluation framework</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 35</span></td>
    <td class="tg-0pky">Sunday, August 28</td>
    <td class="tg-0pky">Saturday, September 3</td>
    <td class="tg-0pky">Evaluation framework</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Test different approaches using <br>Test different datasets and evaluation metrics</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 36</span></td>
    <td class="tg-0pky">Sunday, September 4</td>
    <td class="tg-0pky">Saturday, September 10</td>
    <td class="tg-0pky">Evaluation framework</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Create a user-friendly library</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 37</span></td>
    <td class="tg-0pky">Sunday, September 11</td>
    <td class="tg-0pky">Saturday, September 17</td>
    <td class="tg-0pky">Debt payback week</td>
    <td class="tg-7p3h">TBD</td>
    <td class="tg-7p3h">TBD</td>
    <td class="tg-7p3h">TBD</td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 38</span></td>
    <td class="tg-0pky">Sunday, September 18</td>
    <td class="tg-0pky">Saturday, September 24</td>
    <td class="tg-0pky">arXiv write-up</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Finalize paper write-up</td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 39</span></td>
    <td class="tg-0pky">Sunday, September 25</td>
    <td class="tg-0pky">Saturday, October 1</td>
    <td class="tg-0pky">arXiv write-up</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Finalize and make the code/repository public</td>
    <td class="tg-7p3h">Group's peer review</td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 40</span></td>
    <td class="tg-0pky">Sunday, October 2</td>
    <td class="tg-0pky">Saturday, October 8</td>
    <td class="tg-0pky">arXiv write-up</td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h">Finalize and make the code/repository public</td>
    <td class="tg-7p3h">Finalize paper write-up</td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 41</span></td>
    <td class="tg-0pky">Sunday, October 9</td>
    <td class="tg-0pky">Saturday, October 15</td>
    <td class="tg-0pky"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 42</span></td>
    <td class="tg-0pky">Sunday, October 16</td>
    <td class="tg-0pky">Saturday, October 22</td>
    <td class="tg-0pky"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 43</span></td>
    <td class="tg-0pky">Sunday, October 23</td>
    <td class="tg-0pky">Saturday, October 29</td>
    <td class="tg-0pky"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 44</span></td>
    <td class="tg-0pky">Sunday, October 30</td>
    <td class="tg-0pky">Saturday, November 5</td>
    <td class="tg-0pky"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 37</span></td>
    <td class="tg-0pky">Sunday, September 11</td>
    <td class="tg-0pky">Saturday, September 17</td>
    <td class="tg-0pky"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 38</span></td>
    <td class="tg-0pky">Sunday, September 18</td>
    <td class="tg-0pky">Saturday, September 24</td>
    <td class="tg-0pky"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 39</span></td>
    <td class="tg-0pky">Sunday, September 25</td>
    <td class="tg-0pky">Saturday, October 1</td>
    <td class="tg-0pky"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
    <td class="tg-7p3h"></td>
  </tr>
</tbody>
</table>

* * * 

_yay_

[back](../)
