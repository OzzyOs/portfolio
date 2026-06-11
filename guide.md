Starting local host;

Install 'http-server' using npm:

`npm install -g http-server`

In order to run the website navigate with the terminal to the portfolio directory:

`cd code/portfolio`

Once in the right directory, run the following command:

`http-server .`

Remember to include the `.` at the end of the command.
The dot (`.`) at the end of the command tells `http-server` to serve files from the current directory. If you
don't include the dot, it will default to serving files from the root directory (`/`), which might not be what you
want if your files are in a subdirectory.