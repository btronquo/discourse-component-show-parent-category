# Discourse Component - Show Parent Category

Originally forked from [Arkshine's discourse-show-parent-category-link](https://github.com/Arkshine/discourse-show-parent-category-link).

## Overview

This Discourse component displays the parent (root) category for each topic row in the topic list on the homepage. This helps users identify the context of topics more clearly, especially when browsing categories with nested subcategories.

## Features

- **Parent Category Display**: Shows the parent (root) category in the topic list on the homepage, providing better context for each topic.
  
- **Bracketed Category Name**: If the parent category name contains text in square brackets, the component will display only the content within those brackets. This can be useful for abbreviating or highlighting specific information.

### Example

For a category named:
`[TOTO] My Super Long Category Name > A topic title`

The displayed result will be:
`[TOTO] A topic title`

This makes it easy to show only the essential information from the category name in the topic list.

## Installation

To install this component, follow these steps:

1. Go to your Discourse Admin Panel.
2. Navigate to **Customize** > **Themes** > **Components**.
3. Click on **Install** and choose **Install from GitHub**.
4. Paste the repository URL: `https://github.com/btronquo/discourse-component-show-parent-category`.
5. Enable the component on your active theme.

## Customization

You can control how the category names are displayed:

- **Full Category Name**: By default, the full category name is shown.
- **Bracket Extraction**: If the category name contains square brackets `[]`, the component will extract and display only the text within the brackets.
  

## Compatibility

- Discourse version: `1.8.0` and above
- Compatible with most Discourse themes and plugins.

## Credits

This component is based on the original work by [Arkshine](https://github.com/Arkshine), adapted and modified by me, **Boris Tronquoy**. 

Thank you to the Discourse community for continued support and improvements.
