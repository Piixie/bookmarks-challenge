# Bookmark Manager

## User Stories

```
As a user
So i can view my bookmarks
I would like to create a list
```
The above user story will use the following **elements**:
* controller
* bookmark class
* bookmark view



- When the user visits bookmarks via the '/bookmarks' path sends the request through to our bookmark manager (aka the controller)
- When the controller gets the request, it asks the `Bookmark` class to give it all the bookmarks, i.e. the controller asks for `Bookmark.all`.
- The `Bookmark` class goes and gets the bookmarks, and gives back all the bookmarks in an array to the controller.
- The controller renders the array of bookmarks to a webpage, which it sends as a response to the user

```
As a user
So i can add new bookmarks
I would like to be able to add to the list
```

```
As a user
So I can delete bookmarks
I would like to be able to retract from the list
```

```
As a user
So i can see the most updated page/information
I would be able to update an existing bookmark
```

```
As a user
So I can summarise the page
I would like to be able to comment on bookmarks
```

```
As a user
So I can organise my bookmarks
I would like to be able to tag bookmarks into categories
```

```
As a user
So I can find a page
I would like to filter existing bookmarks by tag
```

```
As a user
So other people cannot change my bookmarks
I would like to restrict access to only myself
```


<!-- Connect to psql
Create the database using the psql command CREATE DATABASE bookmark_manager;
Connect to the database using the pqsl command \c bookmark_manager;
Run the query we have saved in the file 01_create_bookmarks_table.sql -->
