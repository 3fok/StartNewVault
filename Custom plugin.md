# Banner
- Check and install newest version in:  
	https://github.com/noatpad/obsidian-banners/releases
- Fix properties: 
	- Manual install newest version or add CSS code into .obsidian/snippets/hide_banner_properties.css (then turn on CSS Snippets in Obsidian)
		```css
		.obsidian-banner-wrapper {
		  margin-top: 0px;
		  padding-top: 0px;
		}
		
		.mod-header:has(+ .obsidian-banner-wrapper) {
		  margin-top: var(--banner-height);
		}
		```

- Hide banner properties: 
	- Add CSS code into .obsidian/snippets/hide_banner_properties.css
		```css
		div.metadata-properties > div.metadata-property[data-property-key^="banner"] {
		  display: none;
		}
		```
	- Turn on CSS Snippets in Obsidian