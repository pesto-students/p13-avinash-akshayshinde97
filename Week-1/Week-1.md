
## Week 1 Assignment


## List of Assignments
- [Assignment 1](#assignment-1)
- [Assignment 2](#assignment-2)
- [Assignment 3](#assignment-3)



## Assignment 1

### What is a protocol stack, and how is it used in web development?

A Protocol is agreement between two layers(Application,Network, ect ref. OSI model) of a system/Application to transer data between them.
A protocol stack is an ordered list of protocols that are applied to data.
Let's understand in terms of a simple resquest (REST) over internet between client and server .

| Layer | Protocol |
| ------ | ------ |
| Application | HTTPS, TLS|
| Transport | TCP |
| Network | IP |
| Link | Wireless LAN  |

The above table illustrates the protocol stack . There can be many different examples where the protocol stack can be slightly different,
for sending email(Smtp) and  Sharing file(FTP)  over internet.


## What are the different types of web servers, and how do they differ in terms of functionality and performance?

Web servers are software applications or programs that handle HTTP requests from clients (web browsers or other devices) and serve web pages or other resources in response.
There are several types of open source web servers listed some very popular options below:-

- Apache
- Ngnix
- Caddy


## What is web hosting, and what are the different types of hosting services available for websites?

Web hosting is hosting your application on the web server so that it is accessible on the internet and anyone of the internet can use or app.
There are different types of Hosting services available:-
Here are some common types of web hosting:

-Shared Hosting: multiple websites are hosted on the same server and share its resources (CPU, RAM, etc.).
It is cost-effective and suitable for small websites with moderate traffic. However, since resources are shared, the performance might be affected if other sites on the server experience high traffic.

-VPS (Virtual Private Server) Hosting: VPS hosting divides a physical server into multiple virtual servers, each running its own operating system (OS).
Each VPS has dedicated resources, providing more control and better performance compared to shared hosting. It is suitable for websites that require more control and resources but don't need a dedicated server.

-Dedicated Hosting: Dedicated hosting provides an entire physical server dedicated solely to one website. It offers the highest level of control, performance, and security but comes at a higher cost.
Dedicated hosting is suitable for large websites with high traffic and resource-intensive applications.

-Cloud Hosting:Cloud hosting utilizes a network of interconnected servers to distribute resources and ensure high availability. It offers flexibility and scalability, allowing websites to use resources on-demand.
Cloud hosting is suitable for websites with fluctuating traffic levels and a need for scalability.

-Managed Hosting:
Managed hosting involves the hosting provider handling server maintenance, updates, security, and technical support. It's ideal for users who prefer to focus on their website content and leave server management to the experts.

Certain platforms which offer this type of Hosting services are Hostinger,Digital Ocean,AWS,AZURE.



## What is scaling, and why is it important for web applications? How does scaling differ for vertical and horizontal scaling?

Scaling a hosted app/service/system means increasing it's capabilites to serve the request coming from clients.
It is very important to build a scalable system/Service/App in today's day and age because to make sure our service is avialable,
and working properly we need to scale our service/application.
There are majorly two ways to scale a service:-

-Horizontal scaling:- In this we replicate the servers(cab be web server, email server, file server etc) into
multiple available instances, so that the sudden/increased load can be distributed among them and they all can manage the request coming from clients.

-Vertical Scaling:- In this we increase the power/computation capablities of the single/Multiple server like we can upgrade to better perfroming
cpu or increase the ram of the server and also increase the storage of the server.

Ther can be scenarios where our application/service need to be scalled Horizontally and vertically.


## What is SEO (Search Engine Optimization), and how can web developers optimize their websites for better search engine rankings?

Search Engine Optimization is the practice of optimizing websites to improve their visibility and ranking on search engine results pages. The goal of SEO is to increase organic (non-paid) traffic to a website by making it more relevant and valuable to search engine users.

As a web devloper we can do the following things:-


1. On-Page Optimization: Optimize on-page elements such as title tags, meta descriptions, header tags (H1, H2, etc.), and URL structures. Incorporate target keywords naturally into these elements.

2. Mobile-Friendly Design: Ensure the website is responsive and mobile-friendly as more users are accessing websites on mobile devices.

3. Page Speed Optimization: Optimize website loading speed by compressing images, leveraging browser caching, and using a content delivery network (CDN) to deliver content faster to users.

4. URL Structure: Use descriptive and SEO-friendly URLs that include relevant keywords and accurately reflect the page's content.

5. Internal Linking: Create a logical internal S structure to help search engines understand the website's hierarchy and to distribute link authority across various pages, having site map helps.

6. External Link Building: Encourage natural backlinks from authoritative and relevant websites.

7. Image Optimization: Use descriptive alt tags for images to improve accessibility and help search engines understand the image content.

8. Secure Website: Implement HTTPS to provide a secure browsing experience for users. Google considers HTTPS as a ranking signal.


# Assignment 2
HTML Fundamentals

## List of Assignments

- [Poem Webpage](#poem)
- [Hometown Webpage](#hometown-webpage)
- [Musician Fan Webpage](#Musician-Fan-Webpage)
- [Tables](#tables)
- [News Article Webpage](#News-Article-Webpage)

## Poem Webpage

<pre>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>"I'm Nobody!" by Emily Dickinson</title>
</head>
<body>
    <h1>I'm Nobody! Who are you?</h1>
    <!-- First stanza -->
    <p>
        I'm Nobody! Who are you?<br>
        Are you - Nobody - Too?<br>
        Then there's a pair of us!<br>
        Don't tell! They'd banish us - you know!
    </p>

    <!-- Second stanza -->
    <p>
        How dreary - to be - Somebody!<br>
        How public - like a Frog -<br>
        To tell one's name - the livelong June -<br>
        To an admiring Bog!
    </p>

    <!-- Author and date -->
    <p>
        By <em>Emily Dickinson</em> (1891)
    </p>
</body>
</html>

</pre>


## Hometown Webpage
<pre>
<!DOCTYPE html>
<html>
<head>
  <title>Pune</title>
</head>
<body>
  <h1>Pune</h1>

  <h2>Location</h2>
  <!-- Location of Pune, India -->
  <p>Pune is a city in the western Indian state of Maharashtra. It is the second largest city in the state after Mumbai.</p>

  <h2>About</h2>
  <p>We live in area called Katraj which is know for The Rajiv Gandhi Zoological Park, commonly known as the Rajiv Gandhi Zoo or Katraj Zoo</p>

  <h3>Weather</h3>
  <!-- Weather in Pune -->
  <p>Pune has a pleasant climate, with mild winters and warm summers. The average temperature in January is 20 degrees Celsius (68 degrees Fahrenheit), and the average temperature in July is 28 degrees Celsius (82 degrees Fahrenheit).</p>

  <h3>Population</h3>
  <!-- Population of Pune -->
  <p>The population of Pune is about 10+ million people. It is the seventh most populous city in India.</p>

  <h3>Sports</h3>
  <!-- Sports teams in Pune -->
  <p>Pune is home to many sports teams, including the Pune Warriors India (cricket now discontinued) , the Pune City FC (football), and the Puneri Paltan (kabaddi).</p>

  <h2>Things To Do</h2>
  <!-- Things to do in Pune -->
  <ul>
    <li>Visit the historic landmarks, such as the Shaniwar Wada and the Aga Khan Palace.</li>
    <li>Explore the beautiful parks and nature reserves, such as the Osho Ashram and the Vipassana International Academy.</li>
    <li>Try out the local cuisine and restaurants, such as the Misal Pav and the Pav Bhaji.</li>
  </ul>
</body>
</html>
</pre>


## Musician Fan Webpage
<pre>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calvin Harris - DJ Musician</title>
</head>
<body>
    <!-- Header with musician's name -->
    <header>
        <h1>Calvin Harris</h1>
    </header>

    <!-- Main content -->
    <main>
        <!-- 1st paragraph: Background information -->
        <p>Calvin Harris, born Adam Richard Wiles on January 17, 1984, is a renowned Scottish DJ, record producer, singer, and songwriter.
            He gained international fame for his electronic and dance music tracks and has consistently topped the charts with his infectious beats and innovative soundscapes.
            His contributions to the music industry have earned him numerous awards and accolades, making him one of the most influential figures in contemporary music.</p>

        <!-- 2nd paragraph: Link to Calvin Harris website -->
        <p>For more information about Calvin Harris and his music, you can visit his official website <a href="https://www.calvinharris.com/" target="_blank">here</a>.</p>

        <!-- Page creator -->
        <p>Webpage created by <em>AKSHAY SHINDE<em> </p>
    </main>
</body>
</html>

</pre>

## Tables
<pre>
  <!DOCTYPE html>
<html>
<head>
  <title>Table with 3 rows and 3 columns</title>
</head>
<body>
  <table>
    <tr>
      <td colspan="3">
        <h1>1</h1>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <h1>2</h1>
      </td>
      <td>3</td>
      <td>4</td>
    </tr>
    <tr>
      <td>5</td>
      <td>6</td>
    </tr>
  </table>
</body>
</html>

</pre>

## News Article Webpage

<pre>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Social Network Signup</title>
</head>
<body>
    <div class="container">
        <form action="#" method="post" enctype="multipart/form-data">
            <div class="form-group">
                <label for="fullName">Full Name:</label>
                <input type="text" id="fullName" name="fullName" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="about">About Me:</label>
                <textarea id="about" name="about" rows="3" cols="50"></textarea>
            </div>
            <div class="form-group">
                <label for="picture">Profile Picture:</label>
                <input type="file" id="picture" name="picture">
            </div>
            <div class="form-group">
                <input type="submit" value="Join">
            </div>
        </form>
    </div>
</body>
</html>
</pre>


## Assignment 3
## DevTools


### Situation: You want to inspect the HTML and CSS code of a webpage.
### Question: Which panel in Chrome DevTools should you use to inspect the DOM and CSS of a webpage?
### Answer:
We can use Elements tab in the inspect which is usually the first default tab there you will find right side html source code and right side you will tabs like style(open by default) for css.


### Situation: You suspect that a particular JavaScript function is causing errors on a webpage.
### Question: Which panel in Chrome DevTools should you use to debug the JavaScript code on a webpage?
### Answer:
The Tab: "Sources"

You can select a js file you suspect having error and can use below mentioned features to debug it.
Features available in the "Sources" panel usefull for debugging:

  -Breakpoints: Set breakpoints to pause execution and inspect the state of the code.
  -Step through code: Use buttons like "Step Over," "Step Into," and "Step Out" to navigate through the code line by line.
  -Watch variables: Monitor the values of variables as the code executes.
  -Console: View and interact with the console output and run arbitrary code snippets.
  -Call stack: Understand the order in which functions were called and how they relate to each other.


### Situation: You want to analyze the network traffic of a webpage and find out which requests are taking the longest time to load.
### Question: Which panel in Chrome DevTools should you use to analyze the network requests and responses of a webpage?
### Answer:
The Tab: "Network" panel.
Features in Network tab are:-
- Interact with webpage to record requests (refresh, click links, etc.).
- View list of requests; sort by slowest loading time in "Time" column.
- Click a request for details, headers; "Waterfall" chart offers visual timing.
- Utilize filters, search to focus on specific requests.


### Situation: You want to inspect and manipulate browser storage, such as cookies and local storage.
### Question: Which panel in Chrome DevTools should you use to inspect and manipulate browser storage on a webpage?
### Answer:
Tab:- "Application" panel.
The "Application" panel has sections for different types of storage, such as "Storage," "Cookies," "Cache," etc.
-"Storage" section:- Can interact with "Local Storage," "Session Storage," "IndexedDB," and other types of storage. Click on an item to view its key-value pairs, also can edit or delete the stored data.
-"Cookies" section :-The list of cookies associated with the webpage, also view details, search, edit, add, or remove cookies.
The "Application" panel allows us to clear specific types of storage (e.g., cookies, cache) for the current webpage.


### Situation: You want to optimize the performance of a webpage and identify potential bottlenecks.
### Question: Which panel in Chrome DevTools should you use to analyze the performance of a webpage and identify potential bottlenecks?
### Answer:
Tab:- "Performance" panel.
The  Performance  provides a variety of metrics like:

-Time to First Byte (TTFB): The time it takes for the first byte of the webpage to be received by the browser.
-DOM Content Loaded (DCL): The time it takes for the DOM to be loaded and parsed by the browser.
-Load (DOMContentLoaded + Scripts): The time it takes for the DOM and all scripts to be loaded and executed by the browser.
-First Paint (FP): The time it takes for the first pixel of the webpage to be rendered on the screen.
-First Contentful Paint (FCP): The time it takes for the first piece of content (e.g., text, image, video) to be rendered on the screen.
-Speed Index: A metric that measures the perceived performance of a webpage.
The Performance panel also allows you to see a timeline of all the events that occur during the loading of a webpage.

### Situation: You want to test the security of a webpage and check if it has any vulnerabilities.
### Question: Which panel in Chrome DevTools should you use to analyze the security of a webpage and identify potential vulnerabilities?
### Answer:
Tab:- "Security" panel.
Shows  loaded webpage's security status, including HTTPS usage and mixed content presence.
Helps in addressing mixed content problems impacting security and Inspect SSL/TLS certificates for validity and proper configuration.


### Situation: You want to view and modify the CSS styles of a webpage in real-time.
### Question: Which panel in Chrome DevTools should you use to view and modify the CSS styles of a webpage in real-time?
### Answer:
Tab:- "Elements" panel.
This panel will show the HTML and associated CSS,we can directly edit styles, add new ones, or disable/modify existing rules to see instant visual changes on the page.


### Situation: You want to test how a webpage looks and behaves on different screen sizes.
### Question: Which panel in Chrome DevTools should you use to test the responsiveness of a webpage on different screen sizes?
### Answer:
Tab:- toggle device toolbar icon.

We can use device dropdown to choose from various presets or define custom screen dimensions.
Following things can be done:-
-Responsive Testing: The webpage will be displayed as it would on the selected device/screen size. Adjust the viewport.
-Test Interaction: Interact with the page, and observe how its layout and content respond to changes in screen dimensions.
-Rotate and Emulate: You can also test landscape/portrait orientations.

