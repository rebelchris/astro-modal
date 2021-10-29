# Astro modal component

This component is a reusable Astro compopnent for creating modals.

## How to use it?

```jsx
 ---
// Component Imports
import Modal from '../components/Modal.astro';
---

<Modal id="dialog" open="Open modal">
    <main slot="main">
        <p>Some extra content you would like here</p>
        <hr />
        <img width="60" height="80" src="/assets/logo.svg" alt="Astro logo">
    </main>
    <button slot="close">Close modal</button>
</Modal>
```

## Tell me more

Sure, I wrote a whole blog post on using this [Astro reusable modal component](https://daily-dev-tips.com/posts/reusable-modal-component-in-astro/).
