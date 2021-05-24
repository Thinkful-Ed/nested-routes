# Nested Routes

Add any necessary nested routes to the `<User />` and `<UserPosts />` components.
Also update any links to make sure they use the URL from the nearest parent `Route`.

No need to change `<App />`, `<Users />` or  `<UserProfile />`

Use this starter code for the application. You will, of course, need to add appropriate logic to make the application work.
 
# Specific Instructions
- No need to add `<Router>`, it has been added to index.js
 - Please do not remove the  `data-testid={...}` attributes, they are used by the tests.
 - Please do not remove the `data-testid={...}` attributes they are used by the tests.
 - `/` displays `Users`
 - `/user/:userId` displays `User` and `UserProfile`
    - "Profile" and "Posts" lints use the Route URL
 - `/user/:userId/posts` displays `User` and `UserPosts`
    - Links to posts are use the Route URL
 - `/user/:userId/posts/:postId` displays `User` `UserPosts`, `UserPost`
