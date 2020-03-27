# H

.htaccess
: A directory-level configuration file supported by several web servers, used for the configuration of website access issues, such as URL redirection, URL shortening, access control, and more. A site could have more than one .htaccess file, and the files are placed inside the web tree (i.e., inside directories and their subdirectories). .htaccess files act as a subset of the server’s global configuration file (like httpd.conf) for the directory that they are in, or all subdirectories. The original purpose of .htaccess—reflected in its name—was to allow per-directory access control by, for example, requiring a password to access web content. More commonly, however, the .htaccess files define or override many other configuration settings such as content type, character set, CGI handlers, etc.&nbsp;[†](#w-htaccess)

.htpasswd
: A flat file used to store usernames and password for basic authentication on an Apache HTTP Server. The name of the file is given in the .htaccess configuration, and can be anything although “.htpasswd” is the canonical name. .htpasswd is often maintained with the shell command “htpasswd” which can add, delete, and update users, and will properly encode the password for use (so that it is easily checked, but not reversed back to the original password). The file consists of rows, each row corresponding to a username, followed by a colon, followed by a string containing the hashed password optionally prepended by an algorithm specifier (`$2y$`, `$apr1$`, or `{SHA}`) or salt. The hash historically used “Unix crypt” style with MD5 or SHA1 as common alternatives, although as of version 2.2.18 a variant of MD5 is now the default.&nbsp;[†](#w-htpasswd)

Hackathon
: A Sprint-like event, and often one in which computer programmers and others involved in software development, including graphic designers, interface designers, project managers, domain experts, and others collaborate intensively on software projects. The goal of a hackathon is to create functioning software or hardware by the end of the event.&nbsp;[†](#w-hackathon)

Hacker
: Any skilled computer expert that uses their technical knowledge to overcome a problem. While “hacker” can refer to any skilled computer programmer, the term has become associated in popular culture with a “security hacker,” someone who, with their technical knowledge, uses bugs or exploits to break into computer systems.&nbsp;[†](#w-hacker)

Haml/HAML
: → HTML Abstraction Markup Language

Handlebars
: A templating language. Handlebars templates use expressions in the form of `{{`, content, `}}`, resembling handlebars. ℹ︎&nbsp;[handlebarsjs.com](https://handlebarsjs.com/)

Hard reset
: An early 2000s reset “style sheet” that resets the margins and paddings of all elements (`* { margin: 0; padding: 0; }`).

Hash
: → Number sign

Hash function
: Any function that can be used to map data of arbitrary size to fixed-size values. The values returned by a hash function are called hash values, hash codes, digests, or simply hashes. The values are used to index a fixed-size table called a hash table. Use of a hash function to index a hash table is called hashing or scatter storage addressing. Hash functions and their associated hash tables are used in data storage and retrieval applications to access data in a small and nearly constant time per retrieval, and storage space only fractionally greater than the total space required for the data or records themselves. Hashing is a computationally and storage-efficient form of data access.&nbsp;[†](#w-hash-function)

Hash table
: A data structure that implements an associative array abstract data type, a structure that can map keys to values. A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found. In many situations, hash tables turn out to be more efficient than search trees or any other table lookup structure. For this reason, they are widely used in many kinds of computer software, particularly for associative arrays, database indexing, caches, and sets.&nbsp;[†](#w-hash-table)

Hashbang
: → Shebang

Hashtag
: A type of metadata tag used on social networks such as Twitter and other microblogging services. It lets users apply dynamic, user-generated tagging that helps other users easily find messages with a specific theme or content. Users create and use hashtags by placing an octothorpe (`#`, also called a number sign, or pound sign) usually in front of a word or unspaced phrase in a message. Searching for that hashtag yields each message that someone has tagged with it. A hashtag archive is consequently collected into a single stream under the same hashtag.&nbsp;[†](#w-hashtag)

hasLayout
: A peculiarity in Internet Explorer ≤8 that influences how page elements are drawn or interact. Though some elements “automatically” “have layout,” hasLayout can also be forced by particular CSS properties and declarations. ℹ︎&nbsp;[is.gd/KcpK3B](https://www.sitepoint.com/internet-explorer-haslayout-property/)

HCI
: → Human-Computer Interaction

HDD
: → Hypothesis-Driven Development

Heading content
: Content that defines the header of a section (whether explicitly marked up using sectioning content elements, or implied by the heading content itself), marked up through the `h1`, `h2`, `h3`, `h4`, `h5`, `h6`, and `hgroup` elements.&nbsp;§

Headless
: Software capable of working without a graphical user interface.&nbsp;[†](#w-headless)

HEIC
: → High Efficiency Image Coding

HEIF
: → High Efficiency Image File Format

Helper class
: In software development (object-oriented programming), a class that is used to assist in providing some functionality, which is not the main goal of the application or class in which it is used. An instance of a helper class is called a helper object.&nbsp;[†](#w-helper-class)
: In web development (CSS), a class that has no functional bearing and carries no particular meaning (like `.aux` or `.alt`) but serves as an intentional hook for complementary or alternative styling.

Hick’s Law
: A model describing the time it takes for a person to make a decision as a result of the possible choices they have, asserting that increasing the number of choices will increase decision time logarithmically. Hick’s Law assesses cognitive information capacity in choice reaction experiments. The amount of time taken to process a certain amount of bits in the Hick-Hyman law is known as the rate of gain of information.&nbsp;[†](#w-hicks-law)

Hick-Hyman Law
: → Hick’s Law

Hidden Web
: → Deep Web

High Efficiency Image Coding
: → High Efficiency Image File Format

High Efficiency Image File Format
: A file format for individual images and image sequences. It was developed by the Moving Picture Experts Group (MPEG) and is defined by MPEG-H Part 12 (ISO/IEC 23008-12). The MPEG group claims that twice as much information can be stored in a HEIF image as in a JPEG image of the same size, resulting in a better quality image. HEIF also supports animation, and is capable of storing more information than an animated GIF at a small fraction of the size.&nbsp;[†](#w-heif)

Higher-Order Component
: A function that takes a component and returns a new component.

Higher-Order Function
: A function that either takes one or more functions as arguments (procedural parameters) or that returns a function as its result.&nbsp;[†](#w-higher-order-function)

Hit
: A request to a web server for a file (such as a web page, image, script, or style sheet). There may be many hits per page view since an HTML page can contain multiple files, such as images.&nbsp;[†](#w-hit)

HITS
: → Hyperlink-Induced Topic Search

HOC
: → Higher-Order Component

Hoisting
: A general way of thinking about how execution contexts (specifically the creation and execution phases) work in JavaScript. While conceptually, a strict definition of hoisting suggests that variable and function declarations are physically moved to the top of your code, the variable and function declarations are instead put into memory during the compile phase. Only declarations are hoisted, not initializations.&nbsp;[‡](#m-hoisting)

Holey
: A property of an array that misses elements, and cannot be optimized as effectively anymore.

Home page
: The initial or main web page of a website or browser. The initial page of a website is sometimes called main page as well.&nbsp;[†](#w-home-page)

Home Page Reader
: A discontinued self-voicing web browser designed for people who are blind. It was developed by IBM until 2006.&nbsp;[†](#w-hpr)

Home screen
: The main screen on a mobile operating system or computer program. Home screens are not identical because users can rearrange icons as they please, and home screens often differ across operating systems. Almost every smartphone has some form of home screen, which typically displays links to applications, settings, and notifications.&nbsp;[†](#w-home-screen)

Homepage
: → Website

HomeSite
: A discontinued HTML editor originally developed in 1996 by Nick Bradbury. Unlike WYSIWYG HTML editors such as FrontPage and Dreamweaver, HomeSite was designed for direct editing, or “hand coding,” of HTML and other website languages. After a successful partnership with the company to distribute it alongside its own competing Dreamweaver software, HomeSite was acquired by Macromedia in 2001, after which elements of the software were integrated into Dreamweaver. Following the acquisition of Macromedia by Adobe, the company announced in 2009 that HomeSite would be discontinued.&nbsp;[†](#w-homesite)

Hooking
: A range of techniques used to alter or augment the behavior of an operating system, of applications, or of other software components by intercepting function calls or messages or events passed between software components. Code that handles such intercepted function calls, events, or messages is called a hook. Hooking is used for many purposes, including debugging and extending functionality.&nbsp;[†](#w-hooking)

Hop limit
: → Time to Live

Host
: A computer or other device connected to a computer network. A host may work as a server offering information resources, services, and applications to users or other hosts on the network. Hosts are assigned at least one network address. Network hosts that participate in applications that use the client-server model of computing are classified as server or client systems. Network hosts may also function as nodes in peer-to-peer applications, in which all nodes share and consume resources in an equipotent manner.&nbsp;[†](#w-host)

Houdini
: A set of low-level APIs that give developers the power to extend CSS, providing the ability to hook into the styling and layout process of a browser’s rendering engine. Houdini gives developers access to the CSS Object Model (CSSOM), enabling developers to write code the browser can parse as CSS. The benefit of Houdini is that developers can create CSS features without waiting for web standards specifications to define them and without waiting for every browser to fully implement the features.&nbsp;[‡](#m-houdini) ℹ︎&nbsp;[ishoudinireadyyet.com](https://ishoudinireadyyet.com/)

HPR
: → Home Page Reader

HSTS
: → HTTP Strict Transport Security

HTML
: → HyperText Markup Language

HTML Abstraction Markup Language
: A templating system that is designed to avoid writing inline code in a web document and make the HTML cleaner. Haml gives the flexibility to have some dynamic content in HTML. Similar to other web languages like PHP, ASP, JSP, and template systems like eRuby, Haml also embeds some code that gets executed during runtime and generates HTML code in order to provide some dynamic content.&nbsp;[†](#w-haml) ℹ︎&nbsp;[haml.info](http://haml.info/)

HTML template
: For web components, a way to insert chunks of HTML that are then populated. HTML templates are written using the `template` and `slot` elements.

HTML&nbsp;5
: → HTML

HTML/CSS framework
: A library allowing for easier web design and development using HTML and CSS. Most HTML/CSS frameworks contain at least a grid. More functional frameworks also come with more features and additional JavaScript-based functions, but are mostly design-oriented and focused around interactive UI patterns. This detail differentiates HTML/CSS frameworks from JavaScript frameworks.&nbsp;[†](#w-css-framework)

HTML5
: → HTML

HTML5 Boilerplate
: An HTML, CSS, and JavaScript frontend template for creating HTML websites with cross-browser capability.&nbsp;[†](#w-html5-boilerplate) ℹ︎&nbsp;[html5boilerplate.com](https://html5boilerplate.com/)

HTTP
: → Hypertext Transfer Protocol

HTTP method
: A desired HTTP action to be performed for a given resource. Although they can also be nouns, request methods are sometimes referred to as “HTTP verbs.” Each of them implements a different semantic, but some common features are shared by a group of them: e.g., a request method can be safe, idempotent, or cacheable. The methods are `GET`, `HEAD`, `POST`, `PUT`, `DELETE`, `CONNECT`, `OPTIONS`, `TRACE`, and `PATCH`.&nbsp;[‡](#m-http-method)

HTTP status code
: An HTTP status code is issued by a server in response to a client’s request to the server. The first digit of a status code specifies one of five standard classes of responses. The classes are Informational 1xx, Successful 2xx, Redirection 3xx, Client Error 4xx, and Server Error 5xx. “200 OK“, “301 Moved Permanently”, and “404 Not Found” may be among the most common and known status codes.&nbsp;[†](#w-http-status-code)

HTTP Strict Transport Security
: A web security policy mechanism that helps to protect websites against protocol downgrade attacks and cookie hijacking. It allows web servers to declare that web browsers (or other complying user agents) should interact with it using only HTTPS connections, which provide Transport Layer Security (TLS/SSL), unlike the insecure HTTP protocol used alone. The HSTS policy is communicated by the server to the user agent via an HTTPS response header field named `Strict-Transport-Security`. HSTS policy specifies a period of time during which the user agent should only access the server in a secure fashion.&nbsp;[†](#w-hsts)

HTTP/2
: A major revision of the HTTP network protocol. A major goal of HTTP/2 was to decrease latency so to improve page load speed in web browsers. It derived from the earlier experimental SPDY protocol, originally developed by Google. HTTP/2 was developed by the HTTP Working Group (also called httpbis, where “bis” means “second”) of the Internet Engineering Task Force. HTTP/2 is the first new version of HTTP since HTTP 1.1, which was standardized in 1997 by RFC&nbsp;2068. The HTTP/2 specification was published as in 2015 as RFC&nbsp;7540.&nbsp;[†](#w-http2)

httpd.conf
: The main configuration file for the Apache HTTP Server. ℹ︎&nbsp;[is.gd/asNHfP](https://httpd.apache.org/docs/2.4/configuring.html)

HTTPS
: → Hypertext Transfer Protocol Secure

HTTPS Everywhere
: A browser extension for Chrome, Firefox, Opera, Brave, and Firefox for Android, which is developed collaboratively by the Tor Project and the Electronic Frontier Foundation (EFF). HTTPS Everywhere automatically makes websites use a more secure HTTPS connection instead of HTTP, if they support it. HTTPS Everywhere was first released in 2010.&nbsp;[†](#w-https-everywhere) ℹ︎&nbsp;[eff.org/https-everywhere](https://www.eff.org/https-everywhere)

Human-Computer Interaction
: The study of the design and use of computer technology, focused on the interfaces between people (users) and computers. Researchers in the field of HCI observe the ways in which humans interact with computers and design technologies that let humans interact with computers in novel ways. As a field of research, human-computer interaction is situated at the intersection of computer science, behavioral sciences, design, media studies, and several other fields of study.&nbsp;[†](#w-hci)

Hydration
: Client-side DOM extension and manipulation of server-rendered static HTML.

Hyperlink
: → Link

Hyperlink-Induced Topic Search
: A link analysis algorithm that rates web pages, developed in 1999 by Jon Kleinberg. The idea behind Hubs and Authorities, as HITS is also known, stemmed from a particular insight into the creation of web pages when the Internet was originally forming; that is, certain web pages, known as hubs, served as large directories that were not actually authoritative in the information that they held, but were used as compilations of a broad catalog of information that led users to other authoritative pages. In other words, a good hub represents a page that pointed to many other pages, while a good authority represents a page that is linked by many different hubs.&nbsp;[†](#w-hits)

Hypertext
: Text displayed on a computer display or other electronic devices with references (hyperlinks) to other text that the reader can immediately access. Hypertext documents are interconnected by hyperlinks, which are typically activated by a mouse click, keypress set, or by touching the screen. Apart from text, the term “hypertext” is also sometimes used to describe tables, images, and other presentational content formats with integrated hyperlinks. Hypertext is one of the key underlying concepts of the World Wide Web.&nbsp;[†](#w-hypertext)

HyperText Markup Language
: The standard markup language for documents designed to be displayed in a web browser. HTML can be used together with formatting languages such as Cascading Style Sheets (CSS) and scripting languages such as JavaScript. Web browsers receive HTML documents from a web server or from local storage and render the documents into multimedia web pages. HTML and its elements describe the structure of a web page semantically, and HTML originally included cues for the appearance of the document. HTML was first presented in 1991.&nbsp;[†](#w-html) ℹ︎&nbsp;[html.spec.whatwg.org](https://html.spec.whatwg.org/)

Hypertext Preprocessor
: A general-purpose programming language originally designed for web development. PHP was created in 1994 by Rasmus Lerdorf; the PHP reference implementation is now produced by The PHP Group. PHP originally stood for “Personal Home Page,” but it now stands for the recursive initialism “Hypertext Preprocessor.” PHP code may be executed with a command-line interface (CLI), embedded into HTML code, or used in combination with various web template systems, web content management systems, and web frameworks. PHP code is usually processed by a PHP interpreter implemented as a module in a web server or as a Common Gateway Interface (CGI) executable. The web server outputs the results of the interpreted and executed PHP code, which may be any type of data, such as generated HTML code or binary image data.&nbsp;[†](#w-php) ℹ︎&nbsp;[php.net](https://www.php.net/)

Hypertext Transfer Protocol
: An application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks and references to other resources. Development of HTTP was initiated in 1989 by Tim Berners-Lee at CERN, while the development of early HTTP Requests for Comments (RFCs) was a coordinated effort by the Internet Engineering Task Force (IETF) and the World Wide Web Consortium (W3C), with work later moving to the IETF.&nbsp;[†](#w-http)

Hypertext Transfer Protocol Secure
: An extension of the Hypertext Transfer Protocol (HTTP). HTTPS is used for secure communication over a computer network and widely employed on the Internet. In HTTPS, the communication protocol is encrypted using Transport Layer Security (TLS) or, formerly, its predecessor, Secure Sockets Layer (SSL). The protocol is therefore also often referred to as HTTP over TLS, or HTTP over SSL. The principal motivations for HTTPS are authentication of the accessed website, protection of privacy, and integrity of the exchanged data while in transit. The bidirectional encryption of communications between a client and server protects against eavesdropping and tampering of the communication. The authentication aspect of HTTPS requires a trusted third party to sign server-side digital certificates, which historically was expensive.&nbsp;[†](#w-https)

Hypothesis-Driven Development
: A product development approach based on continuously running experiments to test hypotheses about a product, its users, and the market.

T> Is something important missing, or did you find a mistake? Please [share your thoughts](https://github.com/j9t/web-development-glossary-forum/issues/new) and become a glossary&nbsp;contributor!