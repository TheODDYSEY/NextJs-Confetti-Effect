**Confetti Button Component**

This React component creates a button that, when clicked, activates a confetti effect. It utilizes CSS animations and dynamic DOM manipulation to generate colorful confetti shapes that fall from the top of the screen to the bottom.

### Usage

1. Install dependencies:
   - React
   - Next.js
   - Tailwind CSS

2. Import the `ConfettiButton` component into your application.

3. Place the `ConfettiButton` component within your desired page or component to enable the confetti effect.

### Example

```jsx
// Import the ConfettiButton component
import ConfettiButton from '@/components/confetti-button';

// Create a page or component
export default function HomePage() {
  return (
    <main className="min-h-screen flex flex-col text-center justify-center items-center">
      {/* Add the ConfettiButton component */}
      <ConfettiButton />
    </main>
  );
}
```

### Dependencies

- React: "^17.0.2"
- Next.js: "^12.0.7"
- Tailwind CSS: "^3.0.5"

### Components

#### `ConfettiButton`

This component creates a button that, when clicked, activates a confetti effect.

- Props:
  - None

### CSS Styles

The component utilizes Tailwind CSS for styling, including global styles defined in `globals.css` and custom styles for the confetti effect.

### Implementation Details

- The confetti effect is triggered when the button is clicked.
- Confetti shapes (squares and triangles) are dynamically generated and animated using CSS.
- Each confetti element is positioned randomly within the viewport and falls from top to bottom.
- Confetti elements are removed from the DOM after a set duration (4 seconds).

