# NEXT-JS 
## What does nextjs has that react doesn't?
### Architecture
Orginally React had two components Functional and Class-based.
But now components are also also categorized by where they run, if a component runs on the user's browser its called client-side component but if it runs on a server its called server components.
Next.js automatically converts every new component you create into a server component since server ones are more responsive. 

### Rendering Strategies
While React19 supports server components, next.js extends them.
#### Client Side Rendering
The server sends a basic html and js script which the browser executes to render components.
#### Server Side Rendering
The webpage is rendered on the server before transmitting to browser, the server sends html and js rendered pages over to the client side.

Server Side Rendering will significantly improve the SEO of a website, the website will load faster, CSR will make it impossible to index pages and rank them.

### Routing 
In react you have to install an additional routing package but next.js uses file based routing.
Each folder's name becomes a routes path.
Can create an serverless function by creating an API endpoint simply by creating a file in a folder route.js
It takes care of scaling.

### Scaling
### Automaic Code Splitting
React requires manual code splitting. Next.js automates this porcess. This means that when a user loads a specific page it only loads the code of that specific page which significantly enhances loading time.
### Image Optimazations




