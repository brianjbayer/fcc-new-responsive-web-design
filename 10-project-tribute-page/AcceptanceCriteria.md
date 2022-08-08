# Acceptance Criteria: freeCodeCamp (New) Responsive Web Design Tribute Page Project

https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-tribute-page-project/build-a-tribute-page

---

## Objective
Build an app that is functionally similar to https://tribute-page.freecodecamp.rocks

## Acceptance Criteria
- [X] Your tribute page should have a `main` element with a corresponding `id` of `main`, which contains all other elements
- [X] You should see an element with an `id` of `title`, which contains a string (i.e. text), that describes the subject of the tribute page (e.g. "Dr. Norman Borlaug")
- [X] You should see either a `figure` or a `div` element with an `id` of `img-div`
- [X] Within the `#img-div element`, you should see an `img` element with a corresponding `id="image"`
- [X] Within the `#img-div` element, you should see an element with a corresponding `id="img-caption"` that contains textual content describing the image shown in `#img-div`
- [X] You should see an element with a corresponding `id="tribute-info"`, which contains textual content describing the subject of the tribute page
- [X] You should see an a element with a corresponding `id="tribute-link"`, which links to an outside site, that contains additional information about the subject of the tribute page. HINT: You must give your element an attribute of `target` and set it to `_blank` in order for your link to open in a new tab
- [X] Your #image should use `max-width` and `height` properties to resize responsively, relative to the width of its parent element, without exceeding its original size
- [X] Your img element should be centered within its parent element

## Tests
- You should have a `main` element with an `id` of `main`.
- Your `#img-div`, `#image`, `#img-caption`, `#tribute-info`, and `#tribute-link` should all be descendants of `#main`.
- You should have an element with an `id` of `title`.
- Your `#title` should not be empty.
- You should have a `figure` or `div` element with an `id` of `img-div`.
- You should have an `img` element with an `id` of `image`.
- Your `#image` should be a descendant of `#img-div`.
- You should have a `figcaption` or `div` element with an `id` of `img-caption`.
- Your `#img-caption` should be a descendant of `#img-div`.
- Your `#img-caption` should not be empty.
- You should have an element with an `id` of `tribute-info`.
- Your `#tribute-info` should not be empty.
- You should have an a element with an `id` of `tribute-link`.
- Your `#tribute-link` should have an `href` attribute and value.
- Your `#tribute-link` should have a `target` attribute set to `_blank`.
- Your `img` element should have a `display` of `block`.
- Your `#image` should have a `max-width` of `100%`.
- Your `#image` should have a `height` of `auto`.
- Your `#image` should be centered within its parent.
