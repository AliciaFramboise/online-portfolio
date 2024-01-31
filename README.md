# online-portfolio

This project is an online portfolio that helps you display and manage your artworks.
It also allow people to contact you by sending you an email.
Provides drawings ideas.

This project contains two submodules (front and back)

### Clone this repository

Use the `git clone [repo_url] --recursive` command to fetch the main project and its modules

### Manage submodules

To manage the version to checkout for each submodules, modify the .gitmodules file to point to the correct branch

Keep your main repo updated :
- go to the submodule folder (backend or frontend)
- checkout branch or latest commit
- go to the main repo
- update the reference to the submodule in the main repository `git add backend frontend`
- commit and push to origin

> You should be able to see in the main repo that it is pointing backend and frontend to the latest commit
> example `backend @ b824f0f`
