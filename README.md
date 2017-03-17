# OCR Node - Tesseract API Example
A simple api to convert images to text
Git clone this repo and:
`npm install`

Also install the ocr engine:
`brew install tesseract`

Run locally:
`npm run watch`

To use:

go to postman app and do a POST request to

`http://localhost:5000/api/ocr`

with the body {
	file: 'data:image/jpeg;base64,iVBORw0KGgoAAAANSUhEUgAAA..kJggg=='
}

convert your image to base64 here https://www.base64-image.de/ and just chuck it in the body above