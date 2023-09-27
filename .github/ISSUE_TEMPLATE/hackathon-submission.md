name: Custom Issue Template
description: Provide details about your submission

body:
  - type: input
    id: repo-link-1
    attributes:
      label: Repository Link 1
      description: Provide the first repository link (if any).
      placeholder: "https://github.com/user/repo1"
    validations:
      required: false

  - type: input
    id: repo-link-2
    attributes:
      label: Repository Link 2
      description: Provide the second repository link (if any).
      placeholder: "https://github.com/user/repo2"
    validations:
      required: false

  - type: input
    id: repo-link-3
    attributes:
      label: Repository Link 3
      description: Provide the third repository link (if any).
      placeholder: "https://github.com/user/repo3"
    validations:
      required: false

  - type: input
    id: presentation-link
    attributes:
      label: Presentation Link
      description: Provide the link to your presentation.
      placeholder: "https://example.com/presentation"
    validations:
      required: false

  - type: input
    id: video-link
    attributes:
      label: Video Link
      description: Provide the link to your video.
      placeholder: "https://youtube.com/watch?v=example"
    validations:
      required: false

  - type: textarea
    id: description
    attributes:
      label: Description
      description: Provide a detailed description of your submission.
      placeholder: "Describe your project here..."
    validations:
      required: true

  - type: textarea
    id: team-name
    attributes:
      label: Name of the Team
      description: Provide the name of your team.
      placeholder: "Team XYZ"
    validations:
      required: true

  - type: input
    id: topic-chosen
    attributes:
      label: Topic Chosen
      description: Provide the topic you've chosen for your submission.
      placeholder: "Topic Name"
    validations:
      required: true
