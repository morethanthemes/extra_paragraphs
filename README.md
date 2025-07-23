# Extra Paragraphs

This module provides a set of custom paragraph types to be used with the
[Paragraphs](https://www.drupal.org/project/paragraphs) module.

## Paragraph Types

### Highlight

The "Highlight" paragraph type provides a way to feature a piece of content with
an image, title, body text, and a link. It includes the following fields:

-   **Title** (`field_mt_highlight_title`): The title of the highlight.
-   **Body** (`field_mt_highlight_body`): The main text content.
-   **Image** (`field_mt_highlight_image`): An image to display with the
    highlight.
-   **Image Fit** (`field_mt_highlight_image_fit`): Specifies how the image
    should fit within its container (e.g., "cover", "contain").
-   **Link** (`field_mt_highlight_link`): A URL for a call-to-action or more
    information.

## Installation

1.  Enable the module in the Drupal administration interface, or by running the
    following Drush command:

    ```bash
    drush en extra_paragraphs
    ```

2.  This module requires the following modules to be enabled:

    -   [File](https://www.drupal.org/project/file)
    -   [Image](https://www.drupal.org/project/image)
    -   [Link](https://www.drupal.org/project/link)
    -   [Paragraphs](https://www.drupal.org/project/paragraphs)
    -   [Text](https://www.drupal.org/project/text)

## Configuration

The paragraph types are automatically configured upon installation. You can
manage the fields and display settings for the "Highlight" paragraph type by
navigating to the "Paragraphs types" administration page
(`/admin/structure/paragraphs_type`).
