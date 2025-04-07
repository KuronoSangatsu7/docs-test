# ExifReader Library

ExifReader is a lightweight JavaScript library for extracting EXIF metadata from image files.

## Installation

Install ExifReader using npm:

```bash
npm install exifreader
```

## Usage

Here's a simple example of how to use ExifReader:

```javascript
import ExifReader from 'exifreader';

const input = document.querySelector('input[type="file"]');

input.addEventListener('change', async (event) => {
  const file = event.target.files[0];
  const tags = await ExifReader.load(file);
  console.log(tags);
});
```

## Browser Support

ExifReader is compatible with the latest versions of Chrome, Firefox, Edge, and Safari.

## Documentation

For detailed documentation, visit our [official documentation](https://broken-link-example.com).

## License

ExifReader is released under the MIT License.