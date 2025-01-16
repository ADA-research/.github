# ADA Research Github

## Group Code publishing Guidelines

When you publish a paper (Congrats! 🥳) you probably also have some code that should be published with it. As part of our organisation, you can publish it on our group Github instead. If you developed the code as a repository under your personal account, migrating the repo is quite easy, see Settings -> Danger Zone -> Transfer.

Once transferred, it is imperative to make the repository look neato-burrito by setting up a proper README.md. This is just as necessary as making your paper look clean and readable, as well as to keep the groups' page look structured. So, please read the checklist below carefully, this should take a pro like you only a few minutes to do!

### README Guidelines

- [ ] Is there a README there with a title of the paper, small description of the work, which authors worked on it, where it was published (Preferably with link to the Proceedings of the paper)?
  - [ ] Is there a description on how to cite your paper easily? (Click to copy BibTex entry would be recommended)
- [ ] Is there a section describing the directory structure of the repo? (Something like: "In the example_data folder, we put the data to test the code. The data used in the paper can be found here..") 
- [ ] Is there an installation section on how one should be able to get the code to run?
  - [ ] Usually this comes with an `requirements.txt` or `environment.yml` file to make the life of other devs easier.
- [ ] Is there a small example how one can test that the code runs?
  - [ ] Is this section clear enough that one could easily reproduce the results of the paper with this information?
