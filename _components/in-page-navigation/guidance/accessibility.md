- **Allow keyboard navigation.** Users should be able to navigate between nav items by using the `Tab` key. They should also be able to activate a link when pressing `Enter` on their keyboard. Users should be able to activate hover and focus states with both a mouse and a keyboard.

- **Enable tab order so  keyboard users access the in-page navigation before the main content section.** When a user tabs through a page that contains the in-page navigation component, they should find the in-page navigation before the `main` content. Since the in-page nav will most commonly exist to the right of the content (and follows the `main` element in the markup) this may seem like a tab-order error, but tabbing through the entire page before getting to in-page navigation links is not logical, creates confusion, and diminishes the user experience.

- **Set focus state on section target for keyboard users.** When keyboard users follow an in-page anchor link set the focus state to the link target when the user presses the `Enter` key. When mouse users follow an in-page anchor link the focus should remain on the selected link.