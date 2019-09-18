**Title:** Modular Code

**Statement of Problem:** 
Development does not want to spend the extra resources needed to develop modular components. As a result, shared components are not reused.  

**Context:** 
* There is no corporate mandate for modularized code.
* This is a new product/new code, not a legacy product/code. 
* There is an available repository for sharing code.
* Making code modular takes extra effort and time to develop.
* Time commitments might already have been made for customer deliveries (not changeable).

**Forces:**
* There is a learning curve to writing code that can be reused.
* Extra documentation is required for reusable code.
* Some companies have a common components group that develops reusable code, but others feel that such components should be developed by those business lines that are using the components and a library of common components could be established.
* Developers might not know how to write modular code. Education might be needed. 
* Might be a fear that if not done properly, quality might be impacted.
* Developers might not have incentive to write modular code (due to their tight schedules and lack of a mandate).
* You might be dealing with legacy systems (can't be simply refactored or rewritten).
* Requirements might be different for writing modular code.
* Architectural constraints might impact modularity.
* Developers who develop monolithic code bases might lack the perspective of how modularity might improve how they work.

**Resolution:** 
* Provide incentives to teams to invest in modular code. Modular code is far more reusable. This could work well for large teams when working on modularized projects; team members can focus on their smaller assigned tasks.
    - Developers could get an opportunity to increase their influence in the organization.
* Select certain "success projects," teams that will develop reusable code and demonstrate the long term success. This can help motivate others (they see what is possible and what is in it for them). Transparency is critical.
* Offer education. Modular code is well-understood; there is a lot of literature in favor of this. 
* Accept the cost of modularization, build time into the release schedule.
* Companies moving to use more open source code will appreciate modularity more over time.
* Modular code is easier to work with, especially for larger teams.
* Mitigate risk and fear of quality degradation from accepting InnerSource contributions.
* Establish a checklist of elements to be checked off to classify a component as reusable.
    - There could be requirements on tests, tools and documentation before considering a component as reusable
* Establish standards on testing methodology, labeling of repos.

**Resulting Context:** 
Time is spent making the shared code modular so it can be reused.  

**Author:**  

**Status:** 
Donut


