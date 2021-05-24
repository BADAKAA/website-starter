# website-starter

The perfect template for writing a website. You can choose between css and Scss as well as JavaScript and TypeScript.

TypeScript and 
are recommended for advanced users only.    


If you simply want to use JavaScript, use the file './script.js' file
In that case, you can delete the files:
  './package-lock.json',
  './rollup.config.js'
  './tsconfig.json',
  './package.json',
   and the directory: '/src'.
   
If you want to use TypeScript, write your code into the file: './src/index.ts'. A node.js installation is required for using TypeScript.
Type 'npm i' into your editor's terminal if this is your first time opening this folder.Then, type 'npm run watch' into the terminal every time you open this project in your editor.


The case is similar for css.
If you want to use regular css, simply delete the directory './style' and use the file './style.css'.

If you want to use Scss, write your text into the file: './style/style.scss'.
An Scss-compiler is required for this to work. When using Visual Studio Code, you can simply install the extension: 'Live Sass Compiler' by Glenn Marks.
You have then two options:
  Option 1: You delete the file './style.css' in the root directory, go to the stylesheet import in HTML and link to the css file generated by the compiler.
  Option 2 (Visual Studi Code): Navigate to the menu → file → preferences → settings → extension → live sass copile config → edit in settings.json and insert this code:
    "liveSassCompile.settings.formats": [
        {
          "format": "expanded",
          "extensionName": ".css",
          "savePath": "~/../"
        }
    ]
    
The method udes in option 2 is also described here: https://stackoverflow.com/questions/51696892/how-to-setup-output-path-to-compiled-css-files-using-vscode-live-sass-compiler.

Most importantly: Have fun!