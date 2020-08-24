# Implement new OAuth Provider and refactor Google Sign-In
As a participant of the Google Summer of Code 2020 I helped Catrobat to implement new OAuth Provider (HWIIOAuthBundle) and refactor Google Sign-In. 
I also added a support for Facebook and Apple Log in. Now the users can easier login if they have already existing account on the other platforms like Google, Facebook and Apple.
## Contribution
Here is the description of the contribution of my workflow 
### Step 1 - Choose OAuth Provider
First of all I needed to decide which OAuth provider we should implement. After some research I decided for the HWIOAuthBundle since this bundle is widely used, popular and has a great documentation.
### Step 2 - Install and Configure HWIOAuthBundle
I installed and configured all files in order to get HWIOAuth fully working
### Step 3 - Add Apple Sign in Support
Pocketcode Application is also available and popular on IOS platform because of that we also needed to add the Apple Sign in support.
However HWIOAuth Bundle didnt have a support for Apple SIgn In so I needed to also extend the HWIOAuthBundle and create PR on their repository to make this possible.  Here is the link to that PR: [Apple Sign In support](https://github.com/hwi/HWIOAuthBundle/pull/1639) 
### Step 4 - Remove unused OAuth stuff
Since the new OAuth was fully working I needed to remove unused stuff left from the old OAuth provider.

And here are the pull requests where I implemented all stuff described in the previous steps:
- [Implement New OAuth Provider](https://github.com/Catrobat/Catroweb/pull/573)
- [Remove Unused OAuth stuff](https://github.com/Catrobat/Catroweb/pull/782)

## Other Contributions to the projects
Here is the list of other pull requests which I did and that were not the part of my Google Summer of Code project:
- Redesign of the Project Page: [Project View Update](https://github.com/Catrobat/Catroweb/pull/685)
- New API for the OAUth: [OAuth API](https://github.com/Catrobat/Catroweb/pull/685)
- Handling of the errors which occurre during downloading: [File Download Error Handling](https://github.com/Catrobat/Catroweb/pull/787)
- Deduplication of the project files: [ProjectFiles Deduplication](https://github.com/Catrobat/Catroweb/pull/794)
- Fixed homepage click statistics since they were not working because of the new project list design: [Homepage Click Statistics](https://github.com/Catrobat/Catroweb/pull/830)
- Refactored Click Statistics Page in the admin area [Admin Click Statistics](https://github.com/Catrobat/Catroweb/pull/837)
- Fixed Links at the bottom of the page [Bottom Page Links](https://github.com/Catrobat/Catroweb/pull/838)

