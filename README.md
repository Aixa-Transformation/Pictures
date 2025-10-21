# Pictures

A beautiful gallery to display and expose your picture collection.

## 📸 Features

- **index.html** - A responsive, modern web gallery to display pictures
- **pictures.json** - A JSON file to catalog and manage your pictures

## 🚀 Usage

### Viewing the Gallery

1. Open `index.html` in your web browser to view the gallery
2. Or serve the directory with any web server:
   ```bash
   python3 -m http.server 8080
   ```
   Then visit http://localhost:8080

### Adding Pictures

Edit `pictures.json` to add your own pictures:

```json
{
  "pictures": [
    {
      "title": "Your Picture Title",
      "description": "A description of your picture",
      "url": "path/to/your/image.jpg"
    }
  ]
}
```

## 🎨 Gallery Features

- Responsive grid layout
- Hover effects on picture cards
- Automatic fallback for missing images
- Clean, modern design with gradient background
- Mobile-friendly interface