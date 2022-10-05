# How do we want to build it?

Our idea is to use the PERN framework to build this project.

The **PERN** stack consists of *PostgreSQL, Express, React, and Node. js*. These technologies can be combined to build a full-stack web application with *CRUD operations.*

**CRUD**  is an acronym that comes from the world of computer programming and refers to the four functions that are considered necessary to implement a persistent storage application: *create, read, update and delete.*

As we have narrated in the [README.md](), this is a data search project on selected web pages, and for this, within the team, we have decided to separate the code work into two main fields:

- **1- Backend:**  To develop this part, the team has decided to use web scraping tools to acquire the data previously selected in the different networks.

- **2- Frontend:** To visualize the data acquired and manage them, a dashboard will be created that allows these actions to be carried out.

To develop these different parts, we must create a project architecture or a full stack using different technologies that can be combined for the development of a compact, user-friendly project that allows interaction between different modules.

Next we are going to detail the different technology frameworks that we are going to use:

* A- **Node.js** is an [open-source](https://en.wikipedia.org/wiki/Open-source_software "Open-source software"), [cross-platform](https://en.wikipedia.org/wiki/Cross-platform "Cross-platform"), [back-end](https://en.wikipedia.org/wiki/Front_end_and_back_end "Front end and back end") [JavaScript](https://en.wikipedia.org/wiki/JavaScript "JavaScript") [runtime environment](https://en.wikipedia.org/wiki/Runtime_system "Runtime system") that runs on a [JavaScript Engine](https://en.wikipedia.org/wiki/JavaScript_Engine "JavaScript Engine") (i.e. [V8 engine](https://en.wikipedia.org/wiki/V8_(JavaScript_engine) "V8 (JavaScript engine)")) and executes JavaScript code outside a [web browser](https://en.wikipedia.org/wiki/Web_browser "Web browser"), which was designed to build scalable network applications. Node.js lets developers use JavaScript to write command line tools and for [server-side scripting](https://en.wikipedia.org/wiki/Server-side_scripting "Server-side scripting")—running scripts server-side to produce [dynamic web page](https://en.wikipedia.org/wiki/Dynamic_web_page "Dynamic web page") content before the page is sent to the user's web browser. Consequently, Node.js represents a "JavaScript everywhere" paradigm,[[6]](https://en.wikipedia.org/wiki/Node.js#cite_note-6) unifying [web-application](https://en.wikipedia.org/wiki/Web_application "Web application") development around a single programming language, rather than different languages for server-side and client-side scripts.

* B- **Puppeteer** is a Node library which provides a high-level API to control Chrome or Chromium over the [DevTools Protocol](https://chromedevtools.github.io/devtools-protocol/). Puppeteer runs [headless](https://developers.google.com/web/updates/2017/04/headless-chrome) by default, but can be configured to run full (non-headless) Chrome or Chromium. We use it as web page scraping tool to get the data.

* C- **Express.js**, or simply **Express**, is a [back end](https://en.wikipedia.org/wiki/Front_end_and_back_end "Front end and back end") [web application framework](https://en.wikipedia.org/wiki/Web_application_framework "Web application framework") for building [REST](https://en.wikipedia.org/wiki/Representational_state_transfer "Representational state transfer")ful APIs with [Node.js](https://en.wikipedia.org/wiki/Node.js "Node.js"), released as [free and open-source software](https://en.wikipedia.org/wiki/Free_and_open-source_software) under the [MIT License](https://en.wikipedia.org/wiki/MIT_License "MIT License"). It is designed for building [web applications](https://en.wikipedia.org/wiki/Web_application "Web application") and [APIs](https://en.wikipedia.org/wiki/API "API").[[3]](https://en.wikipedia.org/wiki/Express.js#cite_note-ExpressJS-3) It has been called the [de facto standard](https://en.wikipedia.org/wiki/De_facto_standard "De facto standard") server framework for [Node.js](https://en.wikipedia.org/wiki/Node.js "Node.js").

* D- **React** (also known as **React.js** or **ReactJS**) is a [free and open-source](https://en.wikipedia.org/wiki/Free_and_open-source_software "Free and open-source software") [front-end](https://en.wikipedia.org/wiki/Front_end_and_back_end "Front end and back end") [JavaScript library](https://en.wikipedia.org/wiki/JavaScript_library "JavaScript library")[[3]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-react-3) for building [user interfaces](https://en.wikipedia.org/wiki/User_interfaces "User interfaces") based on UI components. It is maintained by [Meta](https://en.wikipedia.org/wiki/Meta_Platforms "Meta Platforms") (formerly Facebook) and a community of individual developers and companies.[[4]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-4)[[5]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-5)[[6]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-6) React can be used as a base in the development of [single-page](https://en.wikipedia.org/wiki/Single-page_application "Single-page application"), mobile, or server-rendered applications with frameworks like [Next.js](https://en.wikipedia.org/wiki/Next.js "Next.js"). However, React is only concerned with state management and rendering that state to the [DOM](https://en.wikipedia.org/wiki/Document_Object_Model "Document Object Model"), so creating React applications usually requires the use of additional libraries for routing, as well as certain client-side functionality.[[7]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-7)[[8]](https://en.wikipedia.org/wiki/React_(JavaScript_library)#cite_note-8)

* E- **Chakra** is a [free and open-source](https://en.wikipedia.org/wiki/Free_and_open-source "Free and open-source") [JavaScript engine](https://en.wikipedia.org/wiki/JavaScript_engine "JavaScript engine") developed by [Microsoft](https://en.wikipedia.org/wiki/Microsoft "Microsoft") for its [Microsoft Edge Legacy](https://en.wikipedia.org/wiki/Microsoft_Edge "Microsoft Edge") [web browser](https://en.wikipedia.org/wiki/Web_browser "Web browser"). It is a [fork](https://en.wikipedia.org/wiki/Fork_(software_development) "Fork (software development)") of the [same-named JScript engine](https://en.wikipedia.org/wiki/Chakra_(JScript_engine) "Chakra (JScript engine)") used in [Internet Explorer](https://en.wikipedia.org/wiki/Internet_Explorer "Internet Explorer"). Like the [EdgeHTML](https://en.wikipedia.org/wiki/EdgeHTML "EdgeHTML") [browser engine](https://en.wikipedia.org/wiki/Browser_engine "Browser engine"), the declared intention was that it would reflect the "Living Web".[[2]](https://en.wikipedia.org/wiki/Chakra_(JavaScript_engine)#cite_note-2) The core components of _Chakra_ were open-sourced as **ChakraCore**.





