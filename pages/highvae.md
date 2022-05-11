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
  
__(E) Develop and code a general python framework__    
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
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
.tg .tg-g7sd{border-color:inherit;font-weight:bold;text-align:left;vertical-align:middle}
.tg .tg-yla0{font-weight:bold;text-align:left;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">Week</th>
    <th class="tg-0pky">Starts</th>
    <th class="tg-0pky">Ends</th>
    <th class="tg-0pky">Stage</th>
    <th class="tg-0pky">Theory</th>
    <th class="tg-0lax">Development </th>
    <th class="tg-0lax">Writing</th>
    <th class="tg-0lax">Confounds<br></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 11</span></td>
    <td class="tg-0pky">Sunday, March 13</td>
    <td class="tg-0pky">Saturday, March 19</td>
    <td class="tg-0pky">Basic Exploration</td>
    <td class="tg-0pky"></td>
    <td class="tg-0lax"> </td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 12</span></td>
    <td class="tg-0pky">Sunday, March 20</td>
    <td class="tg-0pky">Saturday, March 26</td>
    <td class="tg-0pky">Basic Exploration</td>
    <td class="tg-0pky"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 13</span></td>
    <td class="tg-0pky">Sunday, March 27</td>
    <td class="tg-0pky">Saturday, April 2</td>
    <td class="tg-0pky">Basic Exploration</td>
    <td class="tg-0pky"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-g7sd"><span style="font-weight:bold">Week 14</span></td>
    <td class="tg-0pky">Sunday, April 3</td>
    <td class="tg-0pky">Saturday, April 9</td>
    <td class="tg-0pky"></td>
    <td class="tg-0pky"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 15</span></td>
    <td class="tg-0lax">Sunday, April 10</td>
    <td class="tg-0lax">Saturday, April 16</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 16</span></td>
    <td class="tg-0lax">Sunday, April 17</td>
    <td class="tg-0lax">Saturday, April 23</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 17</span></td>
    <td class="tg-0lax">Sunday, April 24</td>
    <td class="tg-0lax">Saturday, April 30</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 18</span></td>
    <td class="tg-0lax">Sunday, May 1</td>
    <td class="tg-0lax">Saturday, May 7</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 19</span></td>
    <td class="tg-0lax">Sunday, May 8</td>
    <td class="tg-0lax">Saturday, May 14</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 20</span></td>
    <td class="tg-0lax">Sunday, May 15</td>
    <td class="tg-0lax">Saturday, May 21</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 21</span></td>
    <td class="tg-0lax">Sunday, May 22</td>
    <td class="tg-0lax">Saturday, May 28</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 22</span></td>
    <td class="tg-0lax">Sunday, May 29</td>
    <td class="tg-0lax">Saturday, June 4</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 23</span></td>
    <td class="tg-0lax">Sunday, June 5</td>
    <td class="tg-0lax">Saturday, June 11</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 24</span></td>
    <td class="tg-0lax">Sunday, June 12</td>
    <td class="tg-0lax">Saturday, June 18</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 25</span></td>
    <td class="tg-0lax">Sunday, June 19</td>
    <td class="tg-0lax">Saturday, June 25</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 26</span></td>
    <td class="tg-0lax">Sunday, June 26</td>
    <td class="tg-0lax">Saturday, July 2</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 27</span></td>
    <td class="tg-0lax">Sunday, July 3</td>
    <td class="tg-0lax">Saturday, July 9</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 28</span></td>
    <td class="tg-0lax">Sunday, July 10</td>
    <td class="tg-0lax">Saturday, July 16</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 29</span></td>
    <td class="tg-0lax">Sunday, July 17</td>
    <td class="tg-0lax">Saturday, July 23</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 30</span></td>
    <td class="tg-0lax">Sunday, July 24</td>
    <td class="tg-0lax">Saturday, July 30</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 31</span></td>
    <td class="tg-0lax">Sunday, July 31</td>
    <td class="tg-0lax">Saturday, August 6</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 32</span></td>
    <td class="tg-0lax">Sunday, August 7</td>
    <td class="tg-0lax">Saturday, August 13</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 33</span></td>
    <td class="tg-0lax">Sunday, August 14</td>
    <td class="tg-0lax">Saturday, August 20</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 34</span></td>
    <td class="tg-0lax">Sunday, August 21</td>
    <td class="tg-0lax">Saturday, August 27</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 35</span></td>
    <td class="tg-0lax">Sunday, August 28</td>
    <td class="tg-0lax">Saturday, September 3</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 36</span></td>
    <td class="tg-0lax">Sunday, September 4</td>
    <td class="tg-0lax">Saturday, September 10</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 37</span></td>
    <td class="tg-0lax">Sunday, September 11</td>
    <td class="tg-0lax">Saturday, September 17</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 38</span></td>
    <td class="tg-0lax">Sunday, September 18</td>
    <td class="tg-0lax">Saturday, September 24</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-yla0"><span style="font-weight:bold">Week 39</span></td>
    <td class="tg-0lax">Sunday, September 25</td>
    <td class="tg-0lax">Saturday, October 1</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
  </tr>
</tbody>
</table>

* * * 

_yay_

[back](../)
