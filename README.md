# InputGurd.js(Beta)
This will keep your HTML contents safe.

[Try Demo](https://gobzateloon.github.io/examples/InputGurd.html)

* First You Need To Import InputGurd.js To Your Project (Under the Body Tag)

```
    <script src="js/InputGurd.js" ></script>
```

* Thats All For Now. Don't Forget This Is A Beta Version

### Rules
#### If You Delete An Element, Page Will Refresh
#### I Removed Attribute_Lock From These Attributes
* Class
* Style

#### If You Need To Apply InputGurd To Specific Area You Must Try This.
```
    $('#login').InputGurd();
```

#### Add 'NoGurd' Attribute to prevent InputGurd.
```
    <input NoGurd ... >
```

#### Add 'nt-' Prefixes to Attribute for prevent Attribute_Lock.
```
    <input nt-placeholder="Password" ... >
```

#### If You Need To Apply InputGurd To Specific Element.
```
    <input InputGurd ... >
```
