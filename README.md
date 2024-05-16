# blog_web

This template should help get you started developing with Vue 3 in Vite.
# Way - Public

## Todo list

- [ ]  Create a new Vue 3 project
    - [ ]  Install Axios
    - [ ]  Install Tailwind
    - [ ]  Make sure everything is running
- [ ]  Set up the app.vue file (Menu, etc)
- [ ]  Create static sign up page
- [ ]  Create static log in page
- [ ]  Create static feed page
- [ ]  Create static messages page
- [ ]  Create static search page
- [ ]  Make people you may know a component
- [ ]  Make trends a component
- [ ]  Create a toast component
- [ ]  Set up the backend
    - [ ]  Create virtual environment
    - [ ]  Install Django
    - [ ]  Install djangorestframework
    - [ ]  Install djangorestframework-simplejwt
    - [ ]  Install Pillow
    - [ ]  Create Django project
    - [ ]  Set up everything
        - [ ]  Config for jwt
        - [ ]  Config for drf
        - [ ]  Config for csrf and cors
- [ ]  Create app for custom usermodel (remember uuid)
    - [ ]  Add to settings
    - [ ]  Configure jwt urls
- [ ]  Make it possible to sign up
    - [ ]  Implement verification, reset/forgot password and similar (Comes later in the course)
- [ ]  Make it possible to log in (get and refresh token)
- [ ]  Fix buttons in menu when authenticated
- [ ]  Create app for posts
    - [ ]  Database model (remember uuid)
        - [ ]  For the post
        - [ ]  For the attachments
    - [ ]  Set up serializers
    - [ ]  View / URLs
    - [ ]  Get a test feed / show in the frontend (Your own posts)
- [ ]  Make it possible to add text posts
- [ ]  Make it possible to view a profile
    - [ ]  Fix correct name on the profile
    - [ ]  Hide post from when you’re visiting someone elses profile
- [ ]  Set up a simple search
- [ ]  Convert feed to a separate component
- [ ]  Fix the problem with the update on the profile
- [ ]  Set up friendships (model changes)
- [ ]  Make it possible to send friend request
- [ ]  Make it possible to accept friend requests
- [ ]  Prevent sending multiple friendship requests
- [ ]  Update feed to include your friends posts
- [ ]  Make it possible to like a post
- [ ]  Make it possible to discuss a post
    - [ ]  Extra database model (remember uuid)
    - [ ]  Extra field on the post model
    - [ ]  Detail view for post
        - [ ]  Serializer
        - [ ]  View / urls
        - [ ]  New vue file
    - [ ]  Make it possible to add a comment
        - [ ]  View
        - [ ]  Set up the function in the vue file
- [ ]  Create app for messages
    - [ ]  Models (remember uuid)
    - [ ]  Serializers/views/urls for messages
- [ ]  Show messages (list) in the frontend
- [ ]  Show messages (detail) in the frontend
- [ ]  Make it possible to send a message
- [ ]  Make it possible to start a conversation
- [ ]  Fix error on profile page
- [ ]  Trends
- [ ]  Edit profile
    - [ ]  Make it possible to add avatar
- [ ]  Increase post count when creating posts
- [ ]  Set avatar in store when adding / changing avatar
- [ ]  Fix error messages in login / sign up
- [ ]  Change password
- [ ]  Verify your email address on sign up
- [ ]  A user should have a default avatar
- [ ]  Image attachments
- [ ]  Notifications
    - [ ]  Create app
    - [ ]  Set up database model
    - [ ]  Create function for creating a notification
    - [ ]  Load notifiactions on the notification page
    - [ ]  Make it possible to click a notifiaction
    - [ ]  Mark a notifacation as read
- [ ]  Suggest friends
- [ ]  Make it possible to set posts as public/private
    - [ ]  Fix public/private in profile view
    - [ ]  Fix public/private in trends
    - [ ]  Fix public/private in search
- [ ]  Make it possible to post correctly from the feed (not only your profile)
    - [ ]  Combine these to into a component
- [ ]  Prepare for deployment (settings file, no hardcoded urls, etc)
- [ ]  Make it possible to delete a post
- [ ]  Make it possible to report a post
- [ ]  Deploy to Digital Ocean
    - [ ]  Build local, send dist folder
    - [ ]  Run cron jobs
## Recommended IDE Setup



[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
# blog_web_vue
