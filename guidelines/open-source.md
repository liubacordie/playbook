
## Open source guideline

The main purpose of this document, is to establish the way we work in our community oriented open source software (OSS) projects.

### What are the different kind of OSS project Vizzuality work with?
Most of work done at Vizzuality is OSS.

There are 2 kind of projects: 
 - client-related (closed roadmap, not accepting contributions, we don't offer public support).
 - community-oriented: projects maintained by Vizzuality. Open roadmap for anyone who wants to get involve in.
The goal of these projects is to be used not only by Vizzuality but anyone who is interested.
 
This guideline will be focused on community-oriented projects.
  
 
### How do we set a roadmap for a new version?

- Set the scope of the project.
– Once scope is setted we would need to identify a minimum viable product (MVP).
- Define next steps to reach that MVP.
- Split the necessary next steps into smaller tasks to track.

Example:
 - Setting the scope: supporting X type of layer.
 - Defining a MVP: to be able to add and remove this kind of layer.
 - Next steps definition: Create the basic implementation of a plugin to support X type of layer.
 - Tasks: 
  - Adding a new addLayer method to this new plugin.
  - Adding a new removeLayer method to this new plugin.
  - Document those functions.
  - Unit test implementation.
 

### How to contribute?
- Create a Github issue stating the problem/suggestion/question/feature request.
- Maintainers will evaluate this issue can be discarded, resolved or added to the roadmap.
- Once an issue is included in the roadmap, maintainers will either address it themselves or accept contributions (pull requests).

#### Pull Requests

### Who is responsible for the maintenance of the project?

### How are bugs reported and tracked?

### Documentation.

### Quality assurance. What are the minimum requirements?

### Licenses

Usually we use an [MIT License](https://opensource.org/licenses/MIT).
