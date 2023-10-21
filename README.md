# Rickroll
Based on https://github.com/ShatteredDisk/rickroll  

Video from https://twitter.com/DiffusionPics/status/1715441914848383432

## Using with Next.js
```js
/** @type {import('next').NextConfig} */
module.exports = {
	async redirects() {
		return [
			{
				source: '/your-redirect-here',
				destination: 'https://prettylandscapes.com/rickroll.mp4',
				permanent: true,
			}
		];
	},
};

```
