### Isomorphic Rendering

Client and server side using JS, loading performance, simple path to search engine optimization, avoid repeating code and client and server sides.

### No Two-way binding

Unpredictable interactions on the app due to the cascading updates and debugging becomes tricky. Instead, unidirectional data flows, since all the changes flow in one direction.

### JSX

- "HTML" in JS
- Compiles to JS
- More friendly to Designers.
- Easier and faster development.


Instead of embedding JS in HTML, it uses JS to set up the markup. Since JS is more powerful.
"JS" in HTML => "HTML" in JS

It's easier to track error from JSX, since any syntax error would cause the app to not compile. In contrast, HTML syntax errors are usually silent. JSX tells you the line.

**Fail fast, fail loudy** principle.

Integrating interwined concerns aids debugging.

**Virtual DOM**: instead of updating actual DOM. It compares the existing DOM state to what the new should look like and then determine the least expensive way to update the DOM.

**shouldComponentUpdate**: we can declare it to specify when to not change the DOM, even if certain data changes.

**PureRenderMixin** + **inmutability**

**Synthetic events**: abstract away browser-specific event quirks and allow React to optimize the performance of attaching event handlers behind the scene.

**React Native**: for implementing native apps without levering on DOM.
