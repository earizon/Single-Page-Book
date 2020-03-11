Next files is all that needed to create a new Single Page Book Project:
- map_template.html
- map_v1.css
- map_v1.js

************
* Features *
************

  - The full notes-database is just a single human-readable HTML file. 
    No need for local or server apps, a modern (2016+) web browser,
    and a text/html editor is all that needed. 

  - Navigate notes "a la Google maps" by zooming in/out, or 
    "a la Zettlekasten way" by showing related notes.

  - Since html is just pure text, team works is supported through 
    Git/Gitflows.
  
  - Multi-use case: notebook/Zettlekasten/mind-map/dashboard/canvas/...
   
  - Print to paper support:
    print-paper CSS support, useful for first-lectures (start-to-end) of content
    Ex: Two views of the same content:
    -  Map: http://www.oficina24x7.com/Blockchain/ethereum_map.html
    - book: http://www.oficina24x7.com/Blockchain/ethereum_map.pdf
  
  - Shortcut keys for search ("S" and "/")
  
  - Automatic UUID (universal Unique ID) generation in the Help system
  
  - Automatic note background coloring of divs as visual help while "orbiting"/"diving" into 
    the content.

  - Search by text/topics menu can be displayed at page load by just adding the URL 
     parameter '?showSearchMenu'

  - Quick access to topic counters:
    - Total number of topic-related notes is show on the Searh Menu,
      to quickly identify "hot topics".
    - total number of topics linked to the note is shown next to each note.

************
* Planned  *
************
- Improve "topic" handling support by:
  - Allowing meta-topics to organize topics.
  - Allow to reuse third party ontologies already developed by experts.

- Predefined documentation topics (TODO, draft, important, review,  1min/10min/... lecture time,...)

- Allow "development mode" to refresh page when some edition has been
  made to the HTML.

- text description for topics.

- Search by "nearby content" based of similar note-topics.

- Allow to "pop-up" notes in different windows.

************************
* Planned (Far future  *
************************
- IA help system to automatically tag notes by topics.
