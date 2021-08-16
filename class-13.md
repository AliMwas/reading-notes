# LOCAL STORAGE FOR WEB APPLICATIONS
show table of contents
## Introduction to HTML5 Storage 

 What I will call "HTML5 Storage" is a specification called Web Storage. It used to be part of the HTML5 specification but was split into its own specification due to uninteresting political reasons. Some browser vendors also refer to it as "local storage" or "DOM storage". Some related emerging standards make the naming situation more complicated and similar in names, which I will discuss later in this chapter. 
 So what is HTML5 storage? In short, it is a way for web pages to store named key/value pairs locally in the client's web browser. Like cookies, this data will still exist even after you leave the website, close your browser tab, log out of your browser, or anything else. Unlike cookies, this data is never transmitted to a remote web server (unless you make an effort to send it manually). Unlike all previous attempts to provide persistent local storage, it is implemented locally in the web browser, and it can be used even if third-party browser plug-ins are not available.

 With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

**HTML Web Storage Objects**

HTML web storage provides two objects for storing data on the client:

window.localStorage - stores data with no expiration date
window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)
Before using web storage, check browser support for localStorage and sessionStorage:

![storge](https://clementbuchanan.github.io/reading-notes/images/html5.jpg)