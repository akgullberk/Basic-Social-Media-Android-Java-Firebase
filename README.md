# Basic Social Media Java Application
--------------------
# Description

The Basic Social Media Java Application is a simple social media app developed using Java in Android Studio. It features user authentication, post creation, and a feed displaying posts from all users. The application uses Firebase for authentication and Firestore for storing posts and user data.

---------------
# Features

- User Authentication: Sign up and sign in using Firebase Authentication.

- Post Creation: Users can create posts with comments and images.

- Post Feed: Displays all posts from users, sorted by date.

- Image Upload: Upload images to Firebase Storage and display them in posts.

- Logout: Users can log out from their account.
---------
# Usage

- MainActivity

    Handles user sign-in and sign-up.
    Checks if a user is already logged in and redirects them to the FeedActivity.

- FeedActivity

    Displays the list of posts using a RecyclerView.
    Retrieves posts from Firestore and updates the UI.

- UploadActivity

    Allows users to upload images and create new posts.
    Utilizes Firebase Storage for image uploads and Firestore for storing post data.

- PostAdapter

    A custom adapter for the RecyclerView in the FeedActivity.
    Binds post data to the view elements.

- Post Model
  
    Represents a post with attributes like email, comment, and downloadUrl.

----------------

# Screenshots



https://github.com/user-attachments/assets/ad2f6703-94e7-4787-a3b8-705e91810a31

