# CHALLENGE
[ ] Store templates in `tmpl/` and page data in `data/`.
[ ] Add a handler to make the web root redirected to `/view/FrontPage`
[ ] Spruce up the page templates by making them valid `HTML` and adding some `CSS` rules
[ ] Implement inter-page linking by converting instances of `[PageName]` to 

```html
<a href="/view/PageName">PageName</a>
```

(**hint**: could use `regexp.ReplaceAllFunc` to do this)

## File Structure
```
.
├── data
│   ├── newpage.txt
│   ├── TestPage.txt
│   └── test.txt
├── go.mod
├── LICENSE
├── NOTES.md
├── README.md
├── tmpl
│   ├── edit.html
│   └── view.html
├── wiki
└── wiki.go
```
