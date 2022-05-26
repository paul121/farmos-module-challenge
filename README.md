# farmOS module challenge

This challenge consists of developing a [farmOS](https://farmos.org) module that provides a quick form for collecting weather data.

The goal of this challenge is to get an understanding of how you code and demonstrate your ability to use farmOS and some common Drupal APIs.

# Setup

We recommend following our documentation to set up a local [farmOS development environment](https://farmos.org/development/environment/).

# The Challenge

farmOS provides a framework for building "quick forms" for common data entry needs. This allows a simplified and focused UI to be provided for fast and easy recording of common events, while maintaining the underlying flexibility of the generalized Asset and Log data architecture.

**Task: Create a quick form for recording weather events that happen on the farm.**

## Requirements

Your quick form should create an `observation` log with the following required and optional fields populated with user-submitted data:
- `timestamp`: (required) The date and time.
- `name`: (required) A short description of the weather event, eg: "Monday rain storm".
- `quantity`: (optional) a quantity associated with the weather event. The quantity label, measure and units could be hard-coded or configurable by the user. eg: "Air temperature: 15 degrees celsius (temperature)".
- `location` (optional): A location asset that represents where this weather event ocurred.
- `notes`: (optional) Additional notes about the weather event.

Finally, open an issue in this challenge repository with a "feature request" outlining a feature that could be added to the weather quick form. This only needs to be an example, but be creative, the feature should be a practical example of something useful for a farm. Outline the use case, considerations and changes required to implement the feature in the issue description.

Some ideas:
- Display the last-recorded weather event.
- Save a quantity derived from the user input.
- Integrate with a weather API to save the temperature at the given time.

### Bonus

As a bonus, implement one of such features in your quick form. Note that this is **optional**! Being able to effectively communicate a feature's use case, considerations, and planned implementation can be just as valuable as the implementation itself.

## What we're looking for

This task should take 2-3 hours at minimum, but you're free to spend more time if you like. The quick form should be functional and meet the requirements above. Focus on your code quality and readability following best practices. If you run out of time add comments describing your progress and what you would have done if you had more time.

Please include code comments where necessary and maintain a proper Git history with commit messages explaining your process.

## Resources

- [farmOS data model](https://farmos.org/model/)
- [farmOS module development](https://farmos.org/development/module/).
- [farmOS Quick Forms](https://farmos.org/development/module/quick/)


