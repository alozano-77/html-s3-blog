# A Girl's Travel Secret (AGTS)

This is a modified version of Editorial, originally created by [@ajlkn](https://twitter.com/ajlkn) for [HTML5 UP](https://html5up.net).
These some modifications to improve SEO and ease of use.

**Demo:** <https://www.agirlstravelsecrets.com>

## Additional features included

### Site Search Integration

- [jQuery plugin](https://tipue.com/search)
  - No need to use Google provided search
  - Modify `tipuesearch/tipuesearch_content.js`

### Lazy Loaded Images

Images are provided via [lazysizes](https://github.com/aFarkas/lazysizes) using the following code:

```html
<img
 alt=""
  data-sizes="auto"
  data-srcset="small.jpg 500w,
    medium.jpg 640w,
    big.jpg 1024w"
  data-src="medium"
  class="lazyload" />
```

### Google Analytics Integration

Replace the code in `<head>` with the code from Google Analytics.

### Additional Files Needed

To maintain a high SEO, I suggest you include the following files:

- `favicon.ico` - [fiverr](https://www.fiverr.com) was great for this
- `robots.txt` - Modified from [reddit](https://www.reddit.com/robots.txt)
- `sitemap.xml` - Can be created [here](www.xml-sitemaps.com)

## AWS Integration

### Route53 and S3

This can be hosted on an S3 bucket using [AWS static website hosting](https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html).

### CloudFront Training

Additional training on integrating CloudFront can be found from the [SAA-C02 course](https://learn.cantrill.io) from Adrian Cantrill.

### Efficient Image Handling

This was achieved using the [serverless image handler](https://github.com/awslabs/serverless-image-handler) provided from AWS Labs.

## Copyright & License

Copyright (c) 2013-2020 [HTML5 UP](https://htmlup.net) & [A Girl's Travel Secrets](https://www.agirlstravelsecrets.com) - This theme is licensed under both the [MIT and Creative Commons Attribution 3.0](LICENSE). Please note that the terms of the Creative Commons license require that you maintain the footer attribution to freely use this theme.
