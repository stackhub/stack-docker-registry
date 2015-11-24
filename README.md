# Purpose

Run a private Docker Registry with a GUI.

# Usage

Compatability

* [x] StackEngine Container Application Center
* [x] Docker Compose (1)

(1) The environment variables keyed with `stackengine:` will not have any
effect, thus the registry will not scale on a per host basis with 
`docker-compose`

## StackEngine Container Application Center

Copy the file into the Advanced Editor in the Stacks portion of the User 
Interface, save it and click the green deploy button.

## Docker Compose

Run the command `docker-compose up` in this director

# License

MIT
