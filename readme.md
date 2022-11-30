## Project Idea

There's many project we can focus on, in Cybersecurity we can perform:

- A port scanner
- A communication with a vulnerability informations db API (like Metasploit)
- Combine both above
- Create our own VPN
- Create a keylogger

**An important point should be the integration with one (or more) of the above functionnalities in a User Interface (UI)**

## Project tree

### API folder

- Contain the relation and request treatment that are returned to the client
- To activate the venv write the command from a terminal on at the apipip folder :
  `source venv/bin/activate`
  and use pip to install package into the venv

### client

- Contain all function to render the User Interface.
- public folder manage all the public content as website's picture or graphic content.
- src folder contains all render functions, pages, routes and style
