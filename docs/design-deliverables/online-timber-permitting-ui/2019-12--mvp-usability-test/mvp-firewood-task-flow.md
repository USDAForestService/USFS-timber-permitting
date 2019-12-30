# Initial task flow for firewood permits
Our goal in this round of research was to create a MVP, end-to-end online firewood permitting process that let us explore our prioritized user stories and test an online process with permit purchasers.

## User stories
The 18F and Forest Service team wrote user stories based on our initial field research and internal discussions. The product team then prioritized which user stories would be most important for an MVP firewood permitting application. For the purposes of this prototype, we focused primarily on permit purchaser needs.

### Highest priority
#### Permit purchaser / Permittee...
* As a permit purchaser, I need to understand that where I intend to get wood is allowed before I purchase a permit, so that I that I can determine whether a firewood permit is right for me and so that I don’t unintentionally break the law.
* As a permit purchaser. I need to understand and agree to firewood harvesting rules so that I can get a valid permit and get wood safely and legally.
* As a permit purchaser, I need a way to pay for my permit online so that I can get my permit quickly.
* As a permittee, I need to understand the rules about where, generally, on FS land I can harvest fuelwood.

### Additional stories
#### Permit purchaser / Permittee...
* As a permit purchaser, I need to be able to choose a permit for the product I want and the area in which I intend to get it so that I can get my product legally.
* As a permit purchaser, I need a secure way to enter required permit information online so that I can get my permit quickly.
* As a permit purchaser, I need to understand how much the wood I’d like to harvest will cost, so that I understand how much money I’ll need to make the purchase.
* As an infirmed permittee, I need to know where I can more easily harvest fuelwood.

## Differences between Christmas tree permits and firewood permits
We wanted to explore if the existing online Christmas tree permitting task flow could be extended to firewood permits. We kept the same basic flow, but made adjustments for firewood permits's unique content and processing needs. This task flow also explored how users could access multiple permit types on the same platform.

### Task order
| [Online Christmas tree permits](https://openforest.fs.usda.gov/christmas-trees/forests) |  [Firewood permit MVP](https://gsa.invisionapp.com/share/R3VA86RNPWK) | Differences |
|---|---|---|
| 1. Select a forest  |  1. Select a forest |  The firewood permit prototype assumes that users would come to this site to  find and buy multiple kinds of permits. The current Open Forest site only sells Christmas tree permits.  |
| -- | 2. Select a permit  | In a world where many permits exist on one platform, the firewood permit prototype introduces a page to learn about permits available from a selected forest.   |
| 2. Forest Christmas tree permit information  | 3. Forest firewood permit information  | We used the Christmas tree permitting information architecure as a starting point. But, firewood is a fundamentally different product than Christmas trees and needed its own content structure.  <br><br> Firewood permits have a longer shelf life than Christmas tree permits, and permit purchasers typically make multiple trips into the forest to collect off their permit. This means firewood permits have more regulations that change with the season (timber sales, fire prevention levels) that purchasers need to be able to access. There is also more regulation on the kinds of wood you can collect that needs to be communicated (dead vs live, allowable species, restricted cutting areas).<br><br>Firewood permit purchasers also need to know how to measure, record, and (sometimes) tag their load to be in compliance.|
|--|4. Sign in with Login.gov|Unlike Christmas tree permits, firewood permits require a valid ID to be issued. We explored what it would be like to verify your identity online with login.gov. The prototype explored reactions and expectations to login.gov, but does not go through the entire authorization and identity proofing process. This would need to be explored in future testing. |
|3. Enter permit information| 5. Enter permit information|Our prototype tested adding additional visual emphasis to the permit they were buying and key conditions of the permit, which could be a helpful checkpoint if multiple permit types are available on the site.|
|4. Agree to rules| 6. Agree to rules| Our prototype adds a section on tagging the load. There also is a future where this page would cover firewood permitting regulations on species restrictions and district-level specifications.|
|5. Pay with pay.gov| 7. Pay with pay.gov|--|
|6. Confirmation and next steps|8. Confirmation and next steps|The printable firewood load tag is attached to the back of the load, while the Christmas tree printable is displayed on the dashboard. |
|7. Print materials|9. Print materials|Firewood permittees will need to print more information than Christmas tree permittees. Often forests will require firewood permit holders tag their loads and have cutting maps or the latest timber sale information on their person, in addition to their permit. Our prototype focused on what a printable load tag would look like.|
