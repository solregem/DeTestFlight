This is testflight for most intents and purposes.
The difference is a few lines of code to make the random number generator use a seed based off the ship's GUID, which changes when a new vessel is launched but not when you revert a launch.
So basically each launch has a unique failure profile that cannot be altered through reverting.