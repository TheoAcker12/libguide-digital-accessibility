# Formatting

## General Guidelines

More detailed information can be found on the [Accessibility Reference Formatting page](https://guides.ou.edu/accessibility-reference/formatting).

### Adaptable Content

One of the most important aspects of accessible design is creating adaptable content. This means that the content can be viewed on different screens and with different zoom levels without decreasing the quality of the user experience.

1.  **Ensure content can be zoomed in up to at least 200% without overflowing containers or requiring horizontal scrolling.** This goes hand-in-hand with general responsive design for mobile users. If you have ever tried to view a PDF on a mobile screen or with a high enough zoom level that you had to scroll horizontally, then you are probably aware of how frustrating it is for any user when content is not adaptable.
2.  **Do not require a particular orientation (horizontal vs. vertical) for viewing your website.**
3.  Create responsive content. **Make sure that your content adjusts and resizes appropriately for very small screens and very large screens.** Many browsers and other applications will allow you to preview your content as it would look for different sizes of screen. You may also be able to mimic this effect by zooming in or out, or by changing the size of your browser or application window.

### Interactive Elements

1.  **Give all interactive elements clear style changes when they are hovered over or receive focus.**
2.  **Visual indications that elements are interactive (links, buttons) should be clear and consistent, and should be reserved for interactive elements.** As a general rule, links should be underlined, as this is a common and well-understood indication. Check out the [WebAIM website](https://webaim.org/) for an excellent example of styling links, especially regarding how they deal with hover and focus.

### Visual Layout vs. Structure

1.  **Make sure the visual layout of the page matches the underlying structure.** Screen reader users and sighted users should have the same experience, and people with low vision who use screen readers will experience both the visual layout and underlying structure at the same time.
2.  **When elements are hidden, make sure they are hidden from only the appropriate audience.** For example, if something should be hidden from everyone, make sure screen reader users will not be able to access it.

## Text

1.  **Avoid underlining text**, as underlines are typically reserved for indicating links.
2.  **Be wary of using strikethrough**. This formatting will not be passed to screen readers, and the line can make the text harder to read. Making the text slightly larger may help with the latter issue.
3.  **Use left alignment.** Left-aligned text maintains consistent character and word spacing. Inconsistently spaced words in justified text can make it difficult to read, and the inconsistent left alignment of centered or right-aligned text is often mistaken for meaningful tab indentations. (If you are writing in text that is supposed to be read from right to left, right alignment will likely be the better choice.)
4.  Both sans serif and serif fonts can be accessible or inaccessible, based on a variety of characteristics. **Highly recommended fonts include Verdana, Lucida Sans or Lucida Grande, and Georgia.** Check out Penn State University's [font sample list](https://accessibility.psu.edu/fontfacehtml/#sample) for more options and comparisons.
5.  Italics can be hard to read on digital platforms. Consider using **bold** or **_bold and italics_** instead.

## Color

1.  **Avoid communicating concepts with color alone.** Readers who are blind, low vision, or colorblind may miss out on important information if it is only shown via color. Secondary indications, such as icons, underlines or contrast changes may be needed to differentiate elements visually. You will also need to consider what screen reader users will hear to make sure they will receive the necessary concepts.
2.  **Consider colorblindness when determining color schemes**, especially when using any sort of color coding. Use colorblindness simulators to see what your color palette will look like to people with various kinds of colorblindness.
3.  **Avoid large blocks of brightly colored text.** These may be too distracting, or even cause a vibration afterimage effect.
4.  **Keep backgrounds subtle.** Bright or strongly textured/patterned backgrounds can make web pages hard to read.
5.  **Ensure background and foreground colors have sufficient contrast.** This also applies to text on top of a background image, though it is harder to check.
6.  **Avoid using contrast that is too extreme.** For example, pure black (#000) against pure white (#FFF) can actually be worse for some users, especially those with dyslexia or light sensitivity.

Check out the Resources page for useful color tools and links to examples.

