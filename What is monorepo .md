2022-11-22
Tags: [[Monorepo]]
Status: #NeedMoreResearch

# What is Monorepo 

- It's a unique repository that contain multipl distinct project well isolated
- Have well definied "code colocation", if not it's consider a big repo 
- A polyrepo creat a lot of project and autonoums team with a lot of differente 
    dependences that differ from one project to another. And in that autonomy 
    lot of close decision to a project are taken not shared with other. 
    Code duplicate is also more present in that type of organisation 
    Inconsistant tooling 

- Make it easier for the team to move from one project to another
- In a Monorepo:
    - there is no overhead in creating new project, the CI is already there
    - Since it's the same repo, a commit in a project is applied in all. Atomic
        commit. 
    - On version for every project, no need to worry about compatibilities 
    - Make it easier for the team to move from one project to another

---
# References
