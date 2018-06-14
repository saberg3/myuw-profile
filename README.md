This component is currently a work in progress, right now it does work as a stand alone component and in tandem with the myuw-app-bar component.

Right now all of the data is hardcoded in as a placeholder, this will be updated soon to use dynamic data pulled in from the MyUW session endpoint.

## Testing

You can view a test of this component being used with the myuw-app-bar by opening index.html


#### Configurable properties

- **Login URL (login-url):** The URL to redirect users to on login
- **Logout URL (logout-url):** The Logout URL to redirect users to on logout
- **Session Endpoint (session-endpoint):** The endpoint URL for session info
- **Open Menu Right (open-right):** Include this attribute if you would like the profile menu to open to the right, instead of left

#### Slots

- **Profile Navigation Item (nav-item):** Add a custom item to the profile button's navigation menu, this slot expects an `<a>` tag