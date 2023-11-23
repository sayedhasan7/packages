*folder-structure-display* is a React component that enables you to visualize hierarchical folder structures with ease.

# Installation

```bash
npm install folder-structure-display
```

# How To Implement 

First Create a Data Array as Given Below :

```javascript
const data = [
  {
    name: "Home",
    children: [
      {
        name: "Section 1",
        children: [
          { name: "H1" },
          { name: "H1" },
          { name: "H1" },
          { name: "H1" },
        ],
      },
    ],
  },
  {
    name: "About",
    children: [
      {
        name: "Section 1",
        children: [
          { name: "H1" },
        ],
      },
    ],
  },
];
```
The data array represents a sample folder structure. *Customize it according to your needs*.

Make Sure The Folder the Data Format is Same as Mentioned Above.

# Usage

```javascript
import React from 'react';
import FolderStructureDisplay from 'folder-structure-display';

const data = [
  {
    name: "Home",
    children: [
      {
        name: "Section 1",
        children: [
          { name: "H1" },
          { name: "H1" },
          { name: "H1" },
          { name: "H1" },
        ],
      },
    ],
  },
  {
    name: "About",
    children: [
      {
        name: "Section 1",
        children: [
          { name: "H1" },
        ],
      },
    ],
  },
];

const App = () => {
  return (
    <div>
      <h1>Your React App</h1>
      <FolderStructureDisplay data={data} />
    </div>
  );
};

export default App;
```

# Props :

 *iconcolor*

 *backgroundcolor*

 *textcolor*
 
 *mainfoldername*
