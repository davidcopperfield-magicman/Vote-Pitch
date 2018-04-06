# Rock The Poll

### A SXSW Hackathon Project 

---

## What It Is

- Decentralized |
- Open Source |
- Modular |
- Secure |

---
@title[Technical Explanation]

<p><span class="slide-title">Code Block</span></p>

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
- [Go Rock The Poll @fa[globe gp-download]](https://voteapp.gq)
- [Register](https://)
  + [Sign In](https://)
- [Review Candidates](https://)
- [Submit Vote](https://)
- [View Vote Confirmation](https://)
- [Custom Logo](https://), [TOC](https://), and [Footnotes](https://)

---

### Questions?

<br>

@fa[twitter gp-contact](@rockthepoll)

@fa[github gp-contact](rockthepoll)

@fa[medium gp-contact](@rockthepoll)

---?image=assets/image/gitpitch-audience.jpg

@title[Go Rock The Poll!]

### Big Thanks To The Rock & Roll Hall of Fame!
### [Go Rock The Poll @fa[globe gp-download]](https://voteapp.gq)

