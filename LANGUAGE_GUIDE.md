# Multi-Language Support Guide

## Overview
The SIBUU Hotel Reservation Platform now supports three languages:
- **English** (EN)
- **አማርኛ** (Amharic - AM)
- **Afaan Oromoo** (Oromo - OM)

## How to Use

### Switching Languages
1. Click the **language button** in the header (shows current language: EN, አም, or OM)
2. The system cycles through: English → አማርኛ → Afaan Oromoo → English
3. Your language preference is automatically saved

### Available Translations
All major UI elements are translated including:
- Navigation menu items
- Page titles and headings
- Form labels and buttons
- Status messages
- Table headers
- Modal dialogs
- Notification messages

## Technical Details

### Files
- `assets/js/translations.js` - Contains all translations
- Translation keys are mapped to text in all three languages

### How It Works
1. Elements with `data-i18n` attribute are automatically translated
2. Language preference is stored in localStorage
3. Translations update immediately when language is changed

### Adding New Translations
To add translations for new elements:

1. Add the translation key to `translations.js`:
```javascript
en: { myNewKey: "My Text" },
am: { myNewKey: "የእኔ ጽሁፍ" },
om: { myNewKey: "Barreeffama Koo" }
```

2. Add `data-i18n` attribute to HTML element:
```html
<h1 data-i18n="myNewKey">My Text</h1>
```

3. The text will automatically update when language changes

### Translation Function
Use the `t()` function in JavaScript:
```javascript
const welcomeText = t('welcome'); // Returns translation based on current language
```

## Language Coverage
- **English**: Default language, 100% coverage
- **አማርኛ**: Ethiopian Amharic translation
- **Afaan Oromoo**: Ethiopian Oromo translation

## Browser Compatibility
Works in all modern browsers that support:
- localStorage API
- ES6 JavaScript
- DOM manipulation

## Future Enhancements
- Date format localization
- Number format localization
- Currency symbol localization
- Right-to-left (RTL) support if needed
- Additional languages as required
