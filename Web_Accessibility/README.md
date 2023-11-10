Web accessibility is one of those aspects of web development where its presence, when implemented correctly, goes unnoticed, but its absence can destroy the user experience.

There are a variety of considerations to make when making a website accessible, ranging from the size and color of the text to invisible properties that are processed by assistive tools such as screen readers.

Paragraph width can also impact readability. It is recommended to have 45 to 85 characters per line, with the ideal being suggested as 65 characters. px is a unit of measure. A more appropriate unit for this purpose is the ch unit, with 1ch being equivalent to the width of the zero (0) character. The ch unit also scales with changes in the value of the font-family or font-size property.

Two colors are contrasting when they are from different segments of the color wheel. Thus, the farther apart the segments, the higher the contrast between the two colors. The difference between the two colors is known as the contrast ratio and a minimum contrast ratio must be met in order to adhere to accessibility standards. The minimum contrast ratio denotes how high the contrast is between the text of certain sizes and width on a specific background. This ratio can range from 1:1, where both compared colors are the same, to 21:1, where the two colors are black and white.

Design Reflecting Structure

An important consideration when applying CSS to a page is the relationship that the CSS stylesheet has with the HTML document’s underlying structure. The order and structure of the HTML elements and CSS properties should match the order and structure of the Document Object Model.

Text should be at least 18px in size, and paragraphs should have a line-height of at least 1.5 to increase the readability of content.

Color contrast between elements should be at least 4.5:1 for standard font sizes.

Interactive elements should have a visual appearance denoting interactivity, such as underlined links and pointer cursor.

Abbreviated content should be given additional content via the \<<abbr>\> element.

When hiding elements from users, use visibility: hidden; or display: none; to hide content from both assisted and non-assisted users.

Visual display should reflect the structure of the presented elements within the HTML to provide navigational coherence for assisted and non-assisted users.

Design pages for consumption in different mediums such as print.
