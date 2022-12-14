# Class 13

## Local Storage and How To Use It On Websites

1. Why would a developer use local storage for a web application?
    [Adding State To The Web: The “Why” Of Local Storage](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
    Because HTTP is stateless - once the application is closed, the state is reset. When storing locally, the state is saved when the application is closed - "remembering" user.

2. What information should not be stored in local storage?
    [Never store sensitive information in LocalStorage](https://stackabuse.com/storing-data-in-the-browser-with-localstorage/)
    Never store sensitive info in local storage: passwords, API Keys, authentication tokens, financial info...

3. Local storage can store what type of data? How would you convert it to that type before storing?
    [Working Around The “Strings Only” Issue](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
    Strings only. You can work around by using JSON.stringify() and JSon.parse() methods.