# Nolan Lewandowski

My favorite music artists are a dj duo that go by the name Sub Zero Project. They produce an electronic genre called hardstyle that is popular in the northern part of Europe and Australia. I recently went to Germany to see them live for the first time. It was the time of my life!

![Picture of Me](DAaSSelfieImage.jpeg)

---

### Table Section

This is a table displaying a few songs that I recommend. It also lists the reasons I recommend them and who made them.

| Song Title | Reasoning | Artist |
| --- | --- | --- |
| Let Go | Ethereal aesthetic | Ark Patrol |
| Clouds | Upbeat and groovy rhythym | Whethan |
| Refuse To Speak | Very energetic electronic bass | Sub Zero Project |
| Mice On Venus | Best video game song to ever exist | C418 |

---

### Quote Section
> The expert at anything was once a beginner. *-Helen Hayes*
>
> To be yourself in a world that is constantly trying to make you something else is the greatest accomplishment. *-Ralph Waldo Emerson*

---

### Code Snippet Section

This is a code snippet for creating a static file server in Node.js.

```
const fileSystem = require('fs');
const http = require('http');

http.createServer((request, response) => {
	fileSystem.readFile(__dirname + request.url, (error, data) => {
		if (error) {
			response.writeHead(404, {
				'Content-Type': 'text/html'
			});
			response.end('404: File not found');
		} else {
			response.writeHead(200, {
				'Content-Type': 'text/html'
			});
			response.end(data);
		}
	});
}).listen(8000);
```

View the code snippet from Pieces here: <https://code.pieces.app/collections/node-js>