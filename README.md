# in React we use MODULAR js. 
what i mean is like we use type='module' attribute in script tag.
# React Projects use BUILD PROCESS.
Browser doesn't support React code.
What i mean is, the code we write is not the code that gets executed in browser
Our code is transformed before it's handed off to the browser.

we could see the tools that enables this feature in package.json like:

"dependencies": {
    "react": "^18.0.0",
    "react-dom": "^18.0.0"
    "react-scripts": blah-blah-blah
}

we could also see the script tags enables us this build process by looking at source code of react project in browser.

Raw, unprocessed React code won't execute in the browser. JSX is not a default JavaScript feature.

