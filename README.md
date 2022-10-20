# Mediahuella Shopify Theme Boiler Plate

This boilerplate was created for make more easy the shopify theme development. This support 2.0 Shopify Stores and uses the following technologies:

- Shopify Liquid
- Tailwind CSS
- Vanilla Javascript 

Instructions

1. Clone the repository with: 
`git clone https://github.com/zobek.dev/shopify-boilerplate`
2. Go to the folder in terminal  and remove git repository in linux or mac with: `rm -r .git`
3. Install node dependencies with: `npm install`
4. Create a devolopment store in your shopify partner account or use the client store for load the new theme.
5. Create the zip file for upload the theme in the store using the following command: `npm run zip`
6. Then install [Theme Kit App](https://apps.shopify.com/theme-kit-access?locale=es) in the store and generate a token.
7. Create the config.yml with shopify theme credentials like the next code
```yaml
development:
  password: THEME-KIT-PASSWORD-TOKEN
  theme_id: "THEME-ID"
  store: STORE-URL
```
8. Then use themekit app from shopify for deploy again the theme and check for errors with `theme deploy`
9. Finally with the command `npm run watch` and another tab `npm run theme` you can start coding an new amazing shopify theme.

Good luck and get funny to working in your theme
