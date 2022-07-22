# goit-markup-hw-03

# Changes to WebStudio Portfolio Website 
• The header, sections and footer are placed on top of each other like bricks. There are no gaps between them. Whole wallpaper, roughly speaking.

• Container (it's an unspoken rule to call it that) - one for the entire site. It is always inside the section. Its main purpose is to limit the width and horizontally align the content. Upper and lower margins/paddings are usually not set.

• The header is a big semantic element, just like the section. It has a small feature. There is a practice when its height is set by link paddings. It's just customary to design links as buttons. Yes, and by increasing the area of the link, we only increase the chance that the user will click on it without problems, we simplify it for him

• Section - an independent semantic block. ALWAYS at 100% screen width. It is she who is given the upper and lower paddings. We create borders for content. It is the section that sets the background, as it is always 100% of the screen width. Images are limited in width.

• Margins to use inside parent blocks. We don't push the parent. You set paddings to the parent, and the children are moved apart by margins. To use margins, try to follow the flow direction - right and bottom (on flex grids, top and left are better). This is not a specific statute. It's just easier to remember at the initial stage. And it’s easier to fix and look for inaccuracies visually, finding them as quickly as possible in devtools

• For links in the header, it is appropriate to set vertical paddings to increase the clickable area.

• There are NO margins between sections on the layout. 94px indents are PADDINGS.

•  The contents of the header, footer, and each of the sections should be wrapped in a div container with a width of 1200px and horizontal paddings of 15px.

• Don't forget to give list items in sections a width. In this case, instead of the justify-content: space-between property, a more reliable option would be to set the indents between the elements (li) using margins (do not forget to reset the extreme indents).

• For the img tag, set the property display: block, max-width: 100%, height: auto.

• We set borders for the elements for which this is required (for example, the header, cards from the portfolio section).

• It is appropriate to wrap the lower part of cards with team members and portfolio cards (elements below the image) in a div, which should be padded on all sides.

• We do NOT set a fixed height (height property) for elements.

• Some elements may have default browser-applied margins and paddings that are visually similar in size to what you want (for example, headings or paragraphs). But you should not hope for this: we reset everything that is by default, and set the indents explicitly - in those cases and in the size in which and in what we need.

• Well, of course, we carefully read the criterias of homework, in particular: child elements do not have external indents margin penetrating the parent; the positioning of elements that cannot be positioned using the standard document flow is done using Flexbox. That is, we use flexes ONLY where there is really a need for them - there is no need to place them everywhere.


# Styling
«B1» Global style reset is allowed using tag selector for such elements as <h1>...<h6>, <p> and <ul>.

«B2» Elements have no margins (margin property) that "break through" the parent element.

«B3» In one-line element collections, the left or right margin (if any) is cleared for all elements.

«B4» The margin property is used for margins between two adjacent elements.

«B5» The padding property is used for the gap between the parent's edge and its child.

«B6» All margins (margin property) and paddings (padding property) of elements are set exactly in line with the layout.

«B7» There is a generic auxiliary class, .container, to center and restrict the width of content.

«B8» The width of the "container" matches the layout, and it is equal to 1200px.

«B9» The "container" contains the header, footer and section content. That is, they are inside it.

«B10» Flexbox is used to arrange elements, but only where necessary. For example, in the header, navigation, lists in sections, etc., that is, where it is impossible to arrange elements horizontally in a customized way.

«B11» Final box sizes in the browser match the layout.

«B12» Elements do not have a fixed height, as it is determined by their content.

«B13» The header has a bottom border, but you need to zoom in very closely to see it.

«B14» Section arrangement is similar to a stack of books, with no margins.

«B15» All sections use one class .section, and they are set top and bottom paddings at 94px, pushing the content inside the section.

«B16» Grids are created using the technique described in the notes and video workshop.

«B17» The cards on the Portfolio page have a border (border property), but only at the bottom of the cards.




