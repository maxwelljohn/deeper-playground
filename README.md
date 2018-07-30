# Deeper playground

Deeper playground is an interactive visualization of neural networks, written in TypeScript using d3.js.  Several research ideas related to neural networks are explored.  For more see deeperplayground.org.

## Development

To run the visualization locally you just need a server to serve all the files from the `dist` directory. You can run `npm install` then `npm run serve` if you don't have one handy. To see the visualization, visit `http://localhost:8080/` on your browser.

When developing, use `npm run serve-watch`. This will start a static server and also watchers to automatically compile the TypeScript, HTML and CSS files
whenever they change.
