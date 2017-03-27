## Swift iOS Programming Challenge

This assessment is meant for you to demonstrate your knowledge of the mobile
development process. You will be creating a filterable and sortable list view. The final
product should be able to be easily built by our team using standard tools. The challenge
should be coded for iOS using Swift.

Requirements:

1. Use Firebase as your REST API and database. http://firebase.io/

2. You will need to create a list view of profiles.

3. Each profile should have all of the following information:
	* A unique integer ID
	* An optional background
color.
	* Gender (Male/Female)
	* Name
	* Age
	* Profile Image
	* Hobbies
4. Each profile should display its respective background color.
	* Males profiles should have a blue background
	* Female profiles should have a green background
	
5. A user should be able to:
	* Filter the list to show only male or female profiles.
	* Clear the filter to show all profiles.
	* Sort the list by age ascending or descending.
	* Sort the list by name ascending or descending.
	* Remove any sorts and go back to the default.
	* Add a new profile using an overlay.
	* Tap on a profile and go to a profile view.
	* Remove a profile from the profile view.
	* Update a profile’s hobbies and background color from the profile view.
	
6. The profile view should display the following information:
	* Gender
	* Name
	* Age
	* Profile Image
	* Hobbies
	
7. The list should be sorted by ID, ascending by default.

8. Any changes to the profiles should be reflected across all running instances of the
app in real time without requiring user interaction
