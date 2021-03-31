# Goal
List GitHub users.  
- Please find out how to search or retrieve users from GitHub in [GitHub User API](https://docs.github.com/en/rest/reference/users).
- Show users in list.
- Limit results to 100 users in total, or you can choose to implement pagination feature (see details in Bonus section).
- In list, each row should at least show info including image from “avatar_url”, “login”, and “site_admin”.
- Implement with multithread (e.g. put time-consuming work in background thread, meanwhile your app should be responsive to user input events).
- Implement in MVVM if possible (or explain for any other architecture of your choice).

# Bonus
Please feel free to ignore bonus items if there is no free time.
- Implement pagination feature by utilizing [GitHub Pagination](https://docs.github.com/en/rest/guides/traversing-with-pagination), please start from "since=0, page size=20"
- Upon clicking on an user in the list, open a page for a single user to show more detailed information.
- Consider how to handle caching or connection issues to improve user experience.

# Note
- Fork this repository to your GitHub account.
- Add ashescat as collaborator to your private repository.
- Write a introduction to all your works in [RESPONSE.md](RESPONSE.md)
- Please leave commit messages to let us know how you construct this app.
- If something is unspecified (UX process, UI specs, ...etc) in exercise, please feel free to make your own assumptions.
- Third party libs are allowed to use.
