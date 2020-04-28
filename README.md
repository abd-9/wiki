# wiki
WIKI Website with Meteor and ReactJs 

Ended requirements:

#Page
- Create, edit, delete and display pages.
- Required data per page.
- Validate entered data on creating and editing a page.
- Metadata depend on the selected category. 
- Display content, title and metadata.
- Content supports rich text editing. 
- When add page it will show on all user (Real time).

#Menu
- Display the titles of all pages on the left side in a menu.
- A click on a title redirects to the specific page.

#Categories
- All Metadata

#User
- Login
- Signup
- Logout
 
#Search
- At the bottom of the menu.
- Full text search on all entries of the pages. (title, content,metadata) // you just have to add any properteis page name to "server\init" => inside "setupPageIndexSearch" to incloud this property to search.
- Display only the pages in the menu, which match the search input.

#Comment 
- Add comment for page.
- Show comment details.
