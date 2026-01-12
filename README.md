# Scratch.rejected
This project is a clean, searchable database of the officially rejected suggestions for the Scratch programming platform. It is designed to help users understand why certain features are not added to Scratch and provides community-sourced workarounds for those limitations.

**Key Features**
* Searchable Database: Quickly find specific blocks or interface features using the search bar.
* Community Voting: Upvote or downvote suggestions to show community sentiment on specific rejections.
* Workarounds Included: Every rejected item includes a practical "Suggested Workaround" to help you achieve your goals within the existing Scratch engine.
* Global Translation: Built-in support for multiple languages using the Google Translate API.
* Dark Mode: A modern, eye-friendly dark theme that respects your system settings or can be toggled manually.

**Technical Details**
[Architecture]
This is a single-file web application built with:
* HTML5/CSS3: Layout and styling.
* Tailwind CSS: Rapid UI development and responsive design.
* Firebase Firestore: Real-time storage for community votes and scores.
* Google Translate API: Integrated via the standard web element for full-page translation.

[Data Structure]
The app uses a local JSON-like array for the primary content to ensure fast loading, which is then synchronized with Firestore to maintain a live "score" for each suggestion.

[Translation System]
The app uses the official Google Translate "Simple" layout.

* Location: Found in the top header.
* Function: When a language is selected, the API dynamically translates all text nodes on the page.
* Performance: Since it uses the native Google element, it handles the heavy lifting of translation without requiring manual API keys for every user.

[How to Use]

* Browse: Use the "Browse All Suggestions" button to enter the main app.
* Filter: Type in the search box to narrow down items by title or reason.
* Learn: Click on a category in the sidebar to jump to specific sections like "Scratch Blocks" or "Website Features."
* Vote: Use the arrow icons next to each item to weigh in on the rejection.

[Safety & Moderation]

This tool is for educational purposes. All content is sourced from the official Scratch "Rejected Suggestions" forum topic. Please refer to the Scratch Community Guidelines when discussing these topics on the official Scratch website.
