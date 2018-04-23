# General

- The system should support multiple photo projects like “Wiki Loves Earth”.
- The system should support multiple languages for the user interface.
- A global organizer should be able to manage all projects.
- A project should have a variable number of organizers.
- A project organizer (or organizer) should be able to manage the projects for which she has the corresponding permissions.
- A project should have a variable number of photos.
- A project should have a variable number of voting rounds.
- A project should have a variable number of jurors.
- A juror should be able to vote for every photo in a project once per round.
- A juror should be able to leave comments per photo.

# Voting

- The voting rounds should build upon each other – the best photos from round `N` should be automatically included in round `N+1`.
- The first round should contain all photos in the project.
- The voting procedure should support two modes:
  - thumbs up / thumbs down
  - a rating scale from 0 to 10

# Users

- A user should be able to log in through the Wikimedia OAuth API.
- A user should be able to change the user interface language.
- A user should be able to hold one or more of the following roles:
  - a global organizer
  - a project organizer
  - a juror

# Project organizers

- A project organizer should be able to import photos.
- A project organizer should be able to delete photos.
