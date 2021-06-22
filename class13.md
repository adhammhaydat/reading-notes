# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS

Persistent local storage is one of the areas where native client applications have held an advantage over web applications.

**Local Storage** is designed to be a dependable, persistent store of data on a client. It is not designed as a "better cookie": that function is designed to be met by Session Storage.

The localStorage object has a few methods we can make use of:
1. localStorage. clear()
2. localStorage. setItem(key, value)
3. localStoage. getItem(key)
4. localStorage. removeItem(key)
5. localStorage. key(index)

![local storeg](https://image.slidesharecdn.com/html5localstorage-160811084833/95/html5-local-storage-10-638.jpg?cb=1471157843)


**How long does local storage persist?**

**localStorage** is similar to sessionStorage , except that while localStorage data has no expiration time, sessionStorage data gets cleared when the page session ends — that is, when the page is closed.

**What is persistent storage in browser?**

Modern web browsers support a number of ways for web sites to store data on the user's computer — with the user's permission — then retrieve it when necessary. This lets you persist data for long-term storage, save sites or documents for offline use, retain user-specific settings for your site, and more.

**Where is local storage stored?**

sqlite in the user's profile folder. Google Chrome records Web storage data in a SQLite file in the user's profile. The subfolder containing this file is " \AppData\Local\Google\Chrome\User Data\Default\Local Storage " on Windows, and " ~/Library/Application Support/Google/Chrome/Default/Local Storage " on macOS.

**Does clearing cache clear local storage?**

Local Storage data will not get cleared even if you close the browser. Because it's stored on your browser cache in your machine. Local Storage data will only be cleared when you clear the browser cache using Control + Shift + Delete or Command + Shift + Delete

![](https://mage2.pro/uploads/default/original/2X/b/b399d692b90a4be986cca8cacf5f3a42cddf14a4.png)

**How do you check local storage is set or not?**
If the given key does not exist in the list associated with the object then this method must return null. ... So, you can: if (localStorage. getItem("infiniteScrollEnabled") === null) { //... }

**How do I keep local storage after refresh?**

localStorage. setItem('initData', JSON. stringify($scope. initData)); is resetting the data each time you refresh.


Historically, web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

* Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over

* Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)

* Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful