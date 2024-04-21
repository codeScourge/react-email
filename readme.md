### setup I did
bunx create-email@lates ./
bun install
bun run dev

### What happens?
Server quits without error message
```
$ email dev
    React Email 2.1.1
    Running preview at:          http://localhost:3000

  ⠏ Getting react-email preview server ready...

shutting down dev server
```

### Setup
Windows 11 v23H2
Bun v1.1.2 (installed in WSL-Ubuntu)


### Workaround
Working with react-mail@1.9.0 works but brings other bugs