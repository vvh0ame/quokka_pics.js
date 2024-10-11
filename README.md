# quokka_pics.js
Web-API for [quokka.pics](https://quokka.pics) which is an API to get cute quokka images

## Example
```JavaScript
async function main() {
	const { QuokkaPics } = require("./quokka_pics.js")
	const quokkaPics = new QuokkaPics()
	const randomImage = await quokkaPics.getRandomImage()
	console.log(randomImage)
}

main()
```
