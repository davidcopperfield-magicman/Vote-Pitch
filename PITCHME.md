# VoteApp

### A SXSW Hackathon Project Presentation

---

## Tips!

<br>

@fa[arrows gp-tip](Press F to go Fullscreen)

@fa[microphone gp-tip](Press S for Speaker Notes)

---

## What It Is

- Decentralized |
- Open Source |
- Modular |
- ? |
- ??? |
- Custom Logo, TOC, and Footnotes |

---
@title[JavaScript Block]

<p><span class="slide-title">JavaScript Block</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---

## How To Use

- [Register](https://github.com/gitpitch/gitpitch/wiki/Code-Presenting)
  + [Sign In](https://github.com/gitpitch/gitpitch/wiki/Code-Delimiter-Slides)
- [Review Candidates](https://github.com/gitpitch/gitpitch/wiki/Slideshow-Custom-CSS)
- [Submit Vote](https://github.com/gitpitch/gitpitch/wiki/Background-Setting)
- [View Vote Confirmation](https://github.com/gitpitch/gitpitch/wiki/Image-Slides#background)
- [Custom Logo](https://github.com/gitpitch/gitpitch/wiki/Logo-Setting), [TOC](https://github.com/gitpitch/gitpitch/wiki/Table-of-Contents), and [Footnotes](https://github.com/gitpitch/gitpitch/wiki/Footnote-Setting)

---

### Questions?

<br>

@fa[twitter gp-contact](@rockthepoll)

@fa[github gp-contact](rockthepoll)

@fa[medium gp-contact](@rockthepoll)

---?image=assets/image/gitpitch-audience.jpg

@title[Go Rock The Poll!]

### Vote App Demo!
### [Go Rock The Poll @fa[globe gp-download]](https://voteapp.gq)

