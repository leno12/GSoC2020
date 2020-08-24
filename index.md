# Implement new OAuth Provider and refactor Google Sign-In
As a participant of the Google Summer of Code 2020 I helped Catrobat to implement new OAuth Provider (HWIOAuthBundle) and refactor Google Sign-In. 
I also added a support for Facebook and Apple Sign in. The process of logging in should be much easier for the users if they have already existing account on some other platform like Google, Facebook, Apple. We also have less code now and the code looks much cleaner then before.
## Contribution
I did the implementation of my project in the following 4 steps
### Step 1 - Choose OAuth Provider
First I needed to decide which OAuth provider we should implement. After some research I decided that I will implement the HWIOAuthBundle since this bundle is widely used, popular and has a great documentation.
### Step 2 - Install and Configure HWIOAuthBundle
I installed HWIOAuthBundle and configured all files in order to get it fully working.
### Step 3 - Add support for Facebook and Apple Sign In
Besides refactoring and replacing the existing Google Sign In I also added support for the Facebook and Apple Sign In.
Pocketcode Application is also available and popular on IOS platform because of that we also needed to add the Apple Sign in support.
However, HWIOAuthBundle didn't have a support for Apple Sign In, so I needed to extend the HWIOAuthBundle and create PR on their repository to make this possible. Here is the link to that PR: [Apple Sign In support](https://github.com/hwi/HWIOAuthBundle/pull/1639)
### Step 4 - Remove unused OAuth stuff
Since the new OAuth was fully working I needed to remove unused stuff left from the old OAuth provider.

 Here is th list of pull requests where the implementation of the steps described above can be found:
- [Implement New OAuth Provider](https://github.com/Catrobat/Catroweb/pull/573)
- [Remove Unused OAuth stuff](https://github.com/Catrobat/Catroweb/pull/782)

## Other Contributions to the project
Besides working on my GSoC project I also did a few other pull requests.
Here is the list of other pull requests which I did and that were not the part of my Google Summer of Code project:
- Redesign of the Project Page: [Project view update](https://github.com/Catrobat/Catroweb/pull/685)
- New API for the OAUth: [OAuth API](https://github.com/Catrobat/Catroweb/pull/685)
- Handling of the errors which occurre during downloading: [File Download Error Handling](https://github.com/Catrobat/Catroweb/pull/787)
- Deduplication of the project files: [Project files deduplication](https://github.com/Catrobat/Catroweb/pull/794)
- Fixed homepage click statistics since they were not working because of the new project list design: [homepage click statistics](https://github.com/Catrobat/Catroweb/pull/830)
- Refactored Click Statistics Page in the admin area [Admin click statistics](https://github.com/Catrobat/Catroweb/pull/837)
- Fixed Links at the bottom of the page [Bottom page links](https://github.com/Catrobat/Catroweb/pull/838)
- Added and implemented API call for the Recommended Projects on the homepage: [Recommended homepage projects](https://github.com/Catrobat/Catroweb/pull/857)

Besides all pull requests stated above I also did a few code reviews.

## Summary
It was such a great experience to be a participant of the Google Summer of Code. I learned a lot of new things here are some of the most interesting for me:
- What is JWT token
- How to genarate, sign, validate JWT tokens
- How OAuth really works under the hood
- How API works and how to implement API calls

And finally I would like to say thanks to the whole Catrobat Team. It was a pleasure and fun to work with You.

