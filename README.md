# curl HTTP cheat sheet

[HTML version here](https://curl.github.io/curl-cheat-sheet/http-sheet.html)

## Markdown attempt

| Verbose                   | Hide progress                   | extra info        | Write output     | Timeout
|---------------------------|---------------------------------|-------------------|------------------|--------------
| -v<br>--trace-ascii file  | -s                              | -w format         | -O<br>-o file    | -m secs
| **POST**                  | **multipart**                   | **PUT**           | **HEAD**         | **custom**
| -d string<br>-d @file     | -F name=value<br>-F name=@file  | -T file           | -I               | -X METHOD
| **Basic auth**            | **read cookies**                | **write cookies** | **send cookies** | **user-agent**
| -u user:password          | -b <file>                       | -c <file>         | -b "c=1; d=2"    | -A string
| **Use proxy**             | **Headers, add/remove**         | **follow redirs** | **gzip**         | **insecure**
| -x host:port              | -H "name: value"<br>-H name:    | -L                | --compressed     | -k
