# Pulse BOT

A simple, interactive chat interface built with HTML, CSS, and JavaScript.

## Features

- Responsive chat UI for user messages
- Auto-expanding textarea for better typing experience
- Displays timestamp for each user message
- Easy to customize and extend

## How It Works

- Users type a message in the textarea and submit via the button.
- Each message is displayed in the chat area with a timestamp.
- The textarea auto-expands as you type.

## Project Structure

```
pulse/
├── index.html         # Main chat interface
├── styles/
│   └── style.css      # Page styling
```

## Usage

1. Open `index.html` in your browser.
2. Type your message and press the send button (▶).
3. Your message will appear in the chat area with the current date and time.

## Customization

- Edit `index.html` to change the UI or add new features.
- Update `styles/style.css` for custom colors, fonts, or layout.
- Extend the JavaScript to add bot responses or connect to a backend.

## Example

```html
<form id="userinput">
  <textarea class="form" id="user" placeholder="type your message" required></textarea>
  <button class="form" id="submit">&#9654;</button>
</form>
```

## Credits

- Built with HTML, CSS, and vanilla JavaScript.

---

**Pulse BOT: Simple, fast, and easy to use.**
