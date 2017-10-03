Condensed technical stuff concerning www

#########################################################################################
NPM: 
- Node Packet Manager
  Der Node Package Manager (npm) ist ein Paketmanager für die JavaScript-Laufzeitumgebung node.js.
Unter dem Namen npm Registry bzw. npm Open Source wird ein Repository betrieben, über das 350.000 Pakete (Stand 13. Januar 2017) unter einer freien Lizenz bereitgestellt werden. Für private Pakete (also nicht Open Source) wird eine kommerzielle Version angeboten. Hinter der Entwicklung und dem Betrieb des Repository steht die Firma npm, Inc. mit Sitz in Oakland, Kalifornien.[6]

Node.js® is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient. Node.js' package ecosystem, npm, is the largest ecosystem of open source libraries in the world.

#########################################################################################
GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere. GitHub enables essentials like repositories, branches, commits, and Pull Requests. You’ll create your own Hello World repository and learn GitHub’s Pull Request workflow, a popular way to create and review code.

Workflow:
- Create a repository
- Add already existing files etc.
- to go on working: 
  - Create a branch (with an describing name for the changes you plan to do in this branch) 
  - Make changes and commit them to this branch
  - Make a pull request for these changes
  - Merge the pull request into the main branch.

#########################################################################################
JavaScript
Assigning functions to variables is one aspect of a programming paradigm called "functional programming". It is one of JavaScript's most powerful features:
var makeSandwich = function() {
  alert("Get bread");
  alert("Spread the butter");
  alert("Spread the jam");
  alert("Cut off the crusts");
  alert("Put in a little bag");
};
makeSandwich();

#########################################################################################
JQuery
For the most part, when we write JavaScript, we want to use it to talk to and affect web pages. We do this via a thing called the Document Object Model or DOM - a series of JavaScript objects that let us interact with every part of the page.

Unfortunately the DOM was put together in a bit of a hurry and is not very easy to use. Douglas Crockford described the DOM as "The worst API ever conceived of". For this reason we tend to use a Javascript wrapper to make talking to the DOM easier.

There are lots of libraries available that help us interact with the DOM such as MooTools, Prototype and Closure. In this course we'll be using a library called JQuery.

