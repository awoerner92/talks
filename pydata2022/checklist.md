# Code Review Checklist

* [ ] Overview over present files and the task  
  * changelist
  * MR's description
  * accompanying ticket (when working with a ticket system, e.g. JIRA)
* [ ] Run the code and reproduce the results
    * [ ] [optional] if GitLab CI is used it might be worth checking the pipeline  
    ❗ fixing the pipeline is the author's responsibility
* [ ] Check the results
      Are they plausible? If not, is there a reason for why they don't match your assumptions or expectations?
* [ ] Ensure comprehension: ask, ask, ask  
      Why has the author decided to do XY, chosen package A instead of B, selected model 42 as baseline,...?
  * [ ] documentation of code and results is sufficient, clear & up-to-date
  * [ ] functions are maneagable & clear
* [ ] Make suggestions that simplify or clarify code
  * function names
  * split complex functions
  * custom implementation can be replaced by a method in package
  * DRY (don't repeat yourself)
  * ...


❗ Don't forget to praise  
-> You can learn as a reviewer (almost) every time  
-> BUT feedback still needs to be honest and authentic

