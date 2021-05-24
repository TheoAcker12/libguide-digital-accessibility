# Content

## Text

For plain text, your biggest concerns will be formatting (e.g. contrast between text color and background color) and readability. The [Accessibility Reference - Text](https://guides.ou.edu/accessibility-reference/content/text) page has more detailed information.

**Refer to the [Formatting Page - Text](https://guides.ou.edu/digital-accessibility/general/formatting#s-lg-box-wrapper-31032640) for formatting guidelines.**

### Readability

1.  **Provide definitions for any unusual words, phrases, idioms, and abbreviations.**
2.  Use the clearest and simplest language possible, or provide simplified versions.
3.  **Identify the language of text** passages, phrases, or other parts of a web page that are written in a different language than the main content. Refer to [Identifying Languages](https://guides.ou.edu/accessibility-reference/content/text#identifying-languages) for more information.
4.  **Do not rely solely on sensory characteristics** (like shape, color, location, etc.) to describe components.
5.  **Do not use all capital letters to emphasize words or phrases.** This makes text harder to read and can potentially cause issues with screen readers.

#### Sensory Characteristics Examples

-   Bad Example: Click the blue button at the top right of the page. (Uses color and visual location)
-   Good Example: Click the Login button. (Avoids sensory characteristics)
-   Good Example: Click the blue Login button at the top right of the page. (Uses sensory characteristics and the actual button name)

## Headings

Headings are a useful visual aid, allowing readers to quickly skim a page to identify the content they are looking for. What you may not realize is that headings provide the same function to screen reader users, assuming they have been implemented correctly. As a matter of fact, almost 70% of screen reader uses say navigating through the headings if the first thing they do when looking for information on a lengthy web page ([WebAIM survey - Finding Information](http://webaim.org/projects/screenreadersurvey8/#finding)).

For the web, headings come in six levels - h1 through h6. Rich text editors will generally provide a way to set these heading levels. It may be helpful to create an outline of your heading structure before writing a page. The [Accessibility Reference - Headings](https://guides.ou.edu/c.php?g=1145200&p=8358736#s-lg-box-wrapper-31173987) has more information.

1.  **Use real headings.** Do not simply format text to look like a heading.
2.  **Do not use headings to apply formatting to non-heading text.** For example, subtitles should be formatted text, rather than actual headings.
3.  **Use the correct heading level.** Do not choose your heading based on formatting, even if you think the formatting for a different heading level looks better.
4.  As a general rule, **every page should have one and only one heading level one** (h1). This heading should provide the title of the page.
5.  **Do not skip heading levels.** For example, a heading level two (h2) should not be followed by a heading level five (h5). (It is fine to skip from a lower level back to a higher level, such as from h5 to h2, however).

## Lists

Like headings, lists are semantic elements. They both provide visual formatting and provide behind-the-scenes structure that screen reader users can access.

1.  **Format all lists as "real" lists.** Rich text editors will provide buttons to create both numbered lists and unordered lists.
2.  **Consider using ordered lists with different numbering systems for each level when creating nested lists**, as screen readers do not usually distinguish levels of indentation. Penn State University provides a useful [example of a nested list](https://accessibility.psu.edu/listshtml/#nested).

## Links

While there are many factors that go into making a good link, these are some of the most important to keep in mind. The [Accessibility Reference - Links](https://guides.ou.edu/c.php?g=1145200&p=8358736#s-lg-box-wrapper-31175045) has more information if you are interested in learning more.

1.  **Make sure all links make sense out of context and out of order**, as they may be presented this way to screen reader users. Avoid phrases like "click here" or "read more," as these are meaningless without context.
2.  **Always indicate when a link opens in a new tab or window, opens a PDF, or downloads a document.** This is one of the biggest accessibility concerns related to links.
3.  **Keep link text short and to the point,** with the most important identifying information at the beginning.
4.  **Do not include the phrase "link" or "link to"** in a link or in the alt text of an image link, as screen readers will already announce it as a link.
5.  **Make sure links are clearly formatted as links.** As a general rule, they should be underlined and in a different color.
6.  **Do not use links as buttons or buttons as links.** If it opens a new page, it should be a link. If it provides a special function, it should be a button.

## Images and Alternative Text

Images are a very common form of non-text content. Accessibility for images is centered around providing alternative text, as blind and low-vision users will not be able to view them. The [Accessibility Reference - Images and Alternative Text](https://guides.ou.edu/c.php?g=1145200&p=8359477#s-lg-box-wrapper-31176566) has more information, but you will most likely want to read and refer to the WAI (Web Accessibility Initiative) Images tutorial.

-   [Images Tutorial](https://www.w3.org/WAI/tutorials/images/) WAI (Web Accessibility Initiative)  
An incredible tutorial on alternative text. Includes a helpful alt decision tree and some tips and tricks, as well as detailed information specific to various types of images.  
When reading the section about complex images, note that approach 4 is not recommended, as longdesc should not be used.
    

Information about the image that does not describe its content or function, such as copyright or source information, does not belong in the alternative text, but should be placed in the image caption. Image captions may also be used for alternative text, depending on the situation.

If you are familiar with the HTML \`longdesc\` attribute, you will want to know that it is not recommended as an accessible alternative. Instead, consider including the description in the normal text of the page next to the image. For reference, see [Longdesc Test Cases - WebAIM](https://webaim.org/techniques/alttext/longdesctestcases.htm).

Title text is the text that appears when you hover the mouse over an object. It may also be called hover text. While it does not introduce any accessibility issues simply by existing, it is not generally accessible for anyone using a screen reader, mobile device, or keyboard (instead of a mouse). If you do include title text, ensure that the content is also presented normally in the page text.

Note that "title" and "alt" are the names of attributes in HTML. Other programs, like Microsoft Word, may refer to these differently.

## Media

1.  Audio-only content should have a written transcript (or other equivalent text alternative).
2.  Video-only content should have an audio track, and/or some form of equivalent text alternative.
3.  Synchronized (audio and video) content should have captions. Prerecorded content should also have an audio track and/or some form of equivalent text alternative (like a transcript).

For more detailed information, see the [Audio and Video Media](https://guides.ou.edu/accessibility-reference/content/media#s-lg-box-wrapper-31176592) section in the Accessibility Reference guide.

### GIFs

Unless you can ensure the following, **_do not use GIFs_**.

1.  The animation stops after 5 seconds, or the user is provided a way to pause it.
2.  The GIF has proper alternative text.
3.  The GIF does not contain blinking or flashing content.

## Tables

Tables are a useful way to structure data, both visually and semantically.

1.  **Keep tables simple.** Limit yourself to a maximum of one header column and one header row. If you need more than these, consider using a sequence of simple tables instead.
2.  **Define column and row headers.** Your content management system should provide a way to set these. If you are editing the HTML directly, use the `<th>` tag and the `scope` attribute.
3.  **Do not put multiple values in the same cell.** Each separate piece of data should have its own cell.
4.  **Use captions and summaries to provide additional information.** Captions will be presented visually on the page, so consider information that would be helpful for all users, such as a title introducing a table. Summaries will only be provided to screen readers. These should not repeat information in the caption, but can be used to supplement that information.

## Other Content

For more information on the content mentioned here, or for other types of content, like block quotes and equations, refer to the [Content pages](https://guides.ou.edu/accessibility-reference/content) in the Accessibility Reference guide.
