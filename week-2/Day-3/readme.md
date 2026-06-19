1.Component Communication
Components pass data down to child components using public properties (@api), and pass data up to parent components by dispatching custom JavaScript events. For independent components that don't share a parent-child relationship, communication is handled via the Lightning Message Service (LMS).
2.Dashboard Design
The dashboard is designed using a grid layout based on the Salesforce Lightning Design System (SLDS) to ensure it is clean, structured, and easy to read. It prioritizes data visibility, ensuring that key metrics and charts adapt fluidly across both desktop and mobile screens.
3.Data Flow Explanation
Data flows from the user's browser interface into the local JavaScript controller via reactive event listeners. From there, the JavaScript layer either uses the wire service or calls backend Apex methods to save or retrieve records from the database.
4.Aura vs LWC
Aura is Salesforce's legacy, heavy framework built on a custom JavaScript abstraction layer that runs slower in modern browsers. LWC is the modern replacement built directly on native browser web standards, making it much faster, lightweight, and easier for web developers to learn.
5.Reflection
Managing custom events and ensuring that the data payload was correctly passed and captured by the parent component.
LWC runs much faster because it uses native browser features, and it uses standard modern JavaScript which makes it easier to write and maintain.
I want to master the Lightning Message Service (LMS) so I can easily send data between components that live on completely different parts of a page.
