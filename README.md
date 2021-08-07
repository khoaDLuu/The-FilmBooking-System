# The-FilmBooking-System
FilmBooking is a system composed of web apps and microservices to provide movie booking service to users.
This monorepo is used for organizational purposes only.

## Web apps
* Admin site: https://movie-admin.herokuapp.com/
* Movie management (for staff): https://movie-management-app.herokuapp.com/
* Movie booking web app (for normal users / guests): https://my-movie-booking.herokuapp.com/

## Development
### How to clone
* Clone the main repo
  ```
  git clone git@github.com:khoaDLuu/The-FilmBooking-System.git
  ```
* Update all submodules
  ```
  git submodule update --init --recursive
  ```

### How to update
* Pull latest changes from remote repos (from this repo and its submodules) (**important!**)
  ```
  git pull --recurse-submodules
  ```
* If the command above doesn't work, try
  ```
  git submodule foreach git pull origin
  ```
* Push to this (remote) monorepo
  ```
  git add -A
  git commit -m "Update message"
  git push origin main
  ```
