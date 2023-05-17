# class 13

## Why would a developer use local storage for a web application?

Local storage allows developers to store and retrieve data in the browser. The data stored in local storage will not expire. This means the data will persist even if the tab or the browser window is closed

## What information should not be stored in local storage?

Given the potential vectors where malicious actors can access information on your browser's local storage, it is easy to see why sensitive information such as Personally Identifiable Information (PII), authentication tokens, user locations and API keys, etc., should never be stored in the local storage.

## Local storage can store what type of data? How would you convert it to that type before storing?

 Additionally, localStorage can only store strings.
Therefore, before storing any other data type in local storage, you need to convert it to a string

## Help from/referenced from
* [Why would a developer use local storage for a web application?](https://www.section.io/engineering-education/how-to-use-localstorage-with-javascript/#:~:text=Local%20storage%20allows%20developers%20to,the%20browser%20window%20is%20closed.)
* [ What information should not be stored in local storage?](https://www.horangi.com/blog/misuse-of-local-storage#:~:text=Given%20the%20potential%20vectors%20where,stored%20in%20the%20local%20storage.)
* [Local storage can store what type of data?](https://blog.logrocket.com/localstorage-javascript-complete-guide/#:~:text=Anyone%20with%20access%20to%20the,to%20convert%20them%20to%20strings.)
* [chatgpt](https://chat.openai.com/)

## Things I want to know or have question about