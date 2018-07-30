LessCSS Issue about Class inside Id Demo
==================================================

If we define less:

```
#main {
    .hello2 {
        border: 3px solid blue;
    }
}
```

Which will not work if we use browser rendering less.

Try it yourself:

```
npm install
npx http-server . -o
```

It will open <http://127.0.0.1:8081> in your browser automatically.
