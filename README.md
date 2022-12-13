# isUrl

```javascript

const isUrl = require("es_valid_url");

const myUrls = [
  "https://google.com",
  "http://google.com",
  "google.com",
  "google.com/path",
  "google.com?id=1",
  "google...com"
];

myUrls.forEach((url) => {
  if (isUrl(url)) {
    // show is url
    console.log(url);
  }
});


}

createPayment()

```