# Day 1

## 1. Library vs Framework

A framework is used for building and deploying an application quickly. When we use a framework, we can use resources to facilitate faster development and a greater user experience. A library is used to enhance the functionality of an application.

## 2. What is Emmet?

Emmet is a set of plug-ins for text editors that allows for high-speed coding and editing in HTML, XML, XSLT, and other structured code formats via content assist.

## 3. What is CDN?

A content delivery network, or content distribution network, is a geographically distributed network of proxy servers and their data centers. The goal is to provide high availability and performance by distributing the service spatially relative to end users.

## 4. What is crossorigin attribute?

The crossorigin attribute sets the mode of the request to an HTTP CORS Request.  

CORS stands for Cross-Origin Resource Sharing, and is a mechanism that allows resources on a web page to be requested from another domain outside their own domain. It defines a way of how a browser and server can interact to determine whether it is safe to allow the cross-origin request. CORS allows servers to specify who can access the assets on the server, among many other things

## 5. What is Integrity attribute?

The integrity attribute allows a browser to check the fetched script to ensure that the code is never loaded if the source has been manipulated.

## 6. Async vs defer

Async allows your script to run as soon as it's loaded, without blocking other elements on the page. Defer means your script will only execute after the page has finished loading. In most cases, async is the better option — but there are exceptions.

## 5. Simple HTML Code

```html
<div id="root"> Hello World! </div>
```

## 6. HTML with Javascript

```html
<div id="root"></div>

<script>
    const heading = document.createElement('h1');

    heading.innerHTML = "Hello World"

    const root = document.querySelector("#root");

    root.appendChild(heading)

</script>
```

## 7. HTML with React

```html
    <div id="root"></div>

    <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>

    <script>
        const heading = React.createElement('h1', {}, 'hello world')

        const root = ReactDOM.createRoot(document.getElementById('root'));

        root.render(heading)
    </script>
```
