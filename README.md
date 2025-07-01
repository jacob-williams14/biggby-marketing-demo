# BIGGBY COFFEE Marketing Content Demo

This repository contains seasonal marketing content data for the BIGGBY COFFEE mobile application. It serves as a demonstration of how marketing content can be ingested from JSON endpoints during development.

## Purpose

This demo repository showcases the ability to dynamically load and display seasonal marketing content in the BIGGBY COFFEE mobile app through JSON data endpoints. It's designed for development environment testing and content management demonstrations.

## Contents

The repository contains seasonal marketing content files:

- `fall-marketing-content.json` - Autumn-themed marketing content
- `winter-marketing-content.json` - Winter-themed marketing content

## Data Structure

Each JSON file contains structured marketing content organized by app sections:

### Home Screen Content

- **Headers**: Personalized messages with `FIRST_NAME` placeholders and guest versions
- **Welcome Messages**: Seasonal greetings and promotional text
- **Product Carousels**: Featured seasonal items with images and titles
- **Menu Categories**: Organized beverage and food categories with icons

### Rewards Program Content

- **Reward Headers**: Personalized and guest messaging
- **Benefits Lists**: Detailed reward program features and offers
- **Promotional Content**: Weekly offers and membership benefits

### Content Types

The JSON structure supports various content types:

- `text` - Simple text content
- `item` - Content with images, icons, and alt text
- `products` - Product carousel items
- `product-groups` - Menu category groupings
- `list` - Structured list items with descriptions

## Usage in Development

This repository demonstrates how the mobile application can:

1. **Fetch Dynamic Content**: Pull marketing content from JSON endpoints
2. **Seasonal Theming**: Switch between seasonal content sets (fall, winter, etc.)
3. **Personalization**: Support both authenticated user content and guest experiences
4. **Content Management**: Update marketing messages without app releases

## Integration Example

The mobile app can consume this content by making HTTP requests to endpoints serving these JSON files, allowing for:

- Real-time content updates
- A/B testing of marketing messages
- Seasonal campaign management
- Personalized user experiences

## Development Environment

This repository is specifically designed for development environment demonstrations, showing how marketing content can be externalized and managed independently from the mobile application code.

---

**Note**: This is a demo repository for development purposes, and this functionality is limited to the development environment.
